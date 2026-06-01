# Anonymity and Identity Online

**Authors:** Florian Ederer (Boston University; CEPR, ECGI, and NBER), Paul Goldsmith-Pinkham (Yale School of Management and NBER), Kyle Jensen (Yale School of Management)

**Status:** Revise and Resubmit, *Review of Economic Studies*

**How to cite:** Ederer, Florian, Paul Goldsmith-Pinkham, and Kyle Jensen (2023). "Anonymity and Identity Online." Working Paper.

**JEL Codes:** C55 (Large Data Sets: Modeling and Analysis), D83 (Search; Learning; Information and Knowledge; Communication), D91 (Role and Effects of Psychological, Emotional, Social, and Cognitive Factors on Decision Making), L86 (Information and Internet Services), Z13 (Economic Sociology; Social and Economic Stratification)

**Keywords:** cryptography, internet privacy, large language models, toxic speech

**Related:** A companion paper, "Anonymous Attention and Abuse," is published in *AEA Papers and Proceedings*, Vol. 115, pp. 188–94, May 2025. DOI: [10.1257/pandp.20251048](https://doi.org/10.1257/pandp.20251048)

---

## Abstract

Economics Job Market Rumors (EJMR) is an online forum and clearinghouse for information on the academic job market for economists. It also includes content that is abusive, defamatory, racist, misogynistic, or otherwise "toxic." Almost all of this content is created anonymously by contributors who receive a four-character username when posting on EJMR. *Using only publicly available data* we show that the statistical properties of the scheme by which these usernames were generated allows the IP addresses from which most posts were made to be determined with high probability. (The scheme changed on May 17, 2023 after the first release of the abstract of this paper on May 16, 2023, and again on July 21, 2023 after the first public presentation of this paper on July 20, 2023.)

We recover tens of thousands of distinct IP addresses of EJMR posters and attribute them to the majority of the roughly 7 million posts made over the past 12 years. We geolocate posts and describe *aggregated* cross-sectional variation — particularly regarding toxic, misogynistic, and hate speech — across sub-forums, geographies, institutions, and IP addresses. Our analysis suggests that content on EJMR comes from all echelons of the economics profession, including, but not limited to, its elite institutions.

---

## 1. Introduction

Economics Job Market Rumors (EJMR, econjobrumors.com) is an anonymous internet message board featuring discussion about economics, the economics profession, and, in particular, the annual job market for PhD economists. The site is popular: in early 2023, SimilarWeb estimated that EJMR received 2.5 million visits per month with an average of 6.45 pages viewed per visit — comparable to the websites of the NBER (1.1 million visits) and AEA (991,000 visits).

EJMR is controversial. It has been called "a breeding ground for personal attacks of an abusive kind" (Blanchard 2017), "a cesspool of misogyny" (Romer 2017), and "evidence of a toxic environment for women in economics" (Wolfers 2017). A substantial fraction of EJMR consists of content that is abusive, defamatory, racist, misogynistic, or otherwise "toxic."

**Main contribution.** We show that EJMR contributors post from locations, institutions, and universities that are intrinsically linked to the academic economics community, including the upper echelons of academia, government, and the private sector. This result contradicts the common claim that EJMR is not representative of the economics profession and that its most frequent users are not actually economists.

**How we do it.** EJMR used a specific algorithm to assign usernames to posts made by anonymous contributors. We show that the properties of this algorithm do not anonymize contributors, but instead allow the IP address from which each post was made to be determined with high probability. We employ a multi-step procedure:

1. We develop GPU-based software to quickly compute the SHA-1 hashes used for the username allocation algorithm on EJMR. In total, we compute almost 3 quadrillion hashes to enumerate all possible IP combinations. For each post, this narrows the set of possible IP addresses from $2^{32}$ (about 4.3 billion) to roughly $2^{16}$ (about 65,000).
2. We measure which IP addresses occur particularly often in a short time window and use the uniformity property of the SHA-1 hash to test whether these IP addresses appear more often than would likely occur by chance.

Our statistical test minimizes the probability of falsely assigning an IP address to a post (p-value thresholds on the order of $10^{-11}$). We assign exactly *zero* posts to the large set of unaddressable "bogon" IP addresses, confirming the method's accuracy.

**Key findings:**
- We recover tens of thousands of distinct IP addresses of EJMR posters.
- Around 15% of posts originate from university networks, including all top-ranked US universities.
- Roughly 11.8% of posts contain text labeled as toxic, 3.3% as misogynistic, and 3.1% as hate speech.
- EJMR posts are more likely to be labeled toxic than 69%, misogynistic than 73%, and hate speech than 95% of the 1,000 most popular subreddits on Reddit.
- Posts mentioning women are substantially more likely to contain hate speech, misogyny, and toxicity; and the *additional* toxicity targeting women on EJMR exceeds that on Reddit.
- Posting activity on EJMR surged during COVID-19 (tripling in the US) and has remained elevated.
- Intrinsic attention-seeking drives posting: when an IP's first topic receives more initial engagement, that IP posts significantly more on *other* threads over the next three days.

---

## 2. Methods

### 2.1 Relationship between IP Addresses and Usernames

The vast majority of EJMR users do not log in with a self-selected username. Instead, EJMR generates usernames, describing the scheme as follows: "EJMR allows you to post anonymously whereby your post enters the database without a record of personally identifiable information like your IP or email address. However to prevent users from voting for themselves and to help users maintain the same 4 letter indentity [sic] within a thread one way encryption is used to create a 4 letter ID which is stored in the database."

**Reverse-engineering the scheme.** The four-letter usernames comprise solely the characters a–f and 0–9, indicating hexadecimal encoding — the standard output format for cryptographic hash functions. We guessed that usernames were generated as:

$$u = S(\mathcal{H}(M(t, a, o)))$$

where $t$ is the topic identifier, $a$ is the visitor's IPv4 address, $o$ is a "salt," $M$ mixes inputs, $\mathcal{H}$ is a hash function, and $S$ extracts a substring.

Using three known (topic ID, IP address, username) triples, we quickly found the scheme:
- $o = \emptyset$ (no salt)
- $M$ = string concatenation: $t$ followed by $a$ in dotted decimal notation
- $\mathcal{H}$ = SHA-1 hash
- $S$ = characters 10–13 (1-based indexing) of the hexadecimal hash

**Example.** A user at IP address 131.111.5.175 posting on topic 227259 receives username **c2b1**, which is the four-character substring at positions 10–13 of the SHA-1 hash of the string "227259131.111.5.175."

This scheme was in use from July 8, 2013 to May 17, 2023. A database administrator error on July 8, 2013 shifted usernames for posts before that date to positions 9–12 instead of 10–13.

The scheme is cryptographically naive: it contains no salt, no stretching function, and no cipher. The username nakedly advertises roughly 16 bits of each post's 32-bit IPv4 address — information that is readily recoverable.

**IP addresses are not people.** IPv4 addresses are assigned to devices, not individuals. Humans change IP addresses when they switch networks, devices, or ISPs. Multiple devices can share the same IP address (via NAT, VPNs, or proxies). Nothing in this paper identifies specific persons.

### 2.2 Mapping Usernames to Candidate IP Addresses

The SHA-1 hash has the "avalanche" property: small input changes produce large output changes, resulting in uniform distribution over the output domain. The EJMR username is a 16-bit (4 hexadecimal character) substring of the 160-bit SHA-1 hash. Due to uniformity, given any (topic, username) pair, approximately $2^{32}/2^{16} = 2^{16} = 65{,}536$ IP addresses could have generated that username — uniformly distributed over the IPv4 space.

**The key insight.** If two posts share the same true origin IP, that IP appears in *both* candidate sets. But "noise" IPs appear at most once across many topics. True IP addresses *stick out* because they explain far more observed usernames across topics than would arise by chance.

**Computational challenge.** To identify the ~65k candidate IPs for each topic-username pair, we must compute the SHA-1 hash for all $2^{32}$ IPv4 addresses for each topic. With roughly 642,000 topics, this requires ~3 quadrillion SHA-1 computations. A single modern CPU core would take over 60 years; we used Nvidia A100 GPUs (6,912 parallel cores each), completing the task in approximately 240 total computing hours. The analysis could be reproduced for roughly $1,000 on AWS P4d instances.

**Verification.** We confirmed the correctness of the scheme through: (1) video demonstrations computing usernames before posting, (2) a screenshot of the EJMR MySQL database posted by the administrator "Kirk" showing SHA-1 hashes alongside topic IDs, and (3) the complete absence of assignments to bogon (unaddressable) IP addresses.

### 2.3 Statistical Test for "Active" IP Addresses

**Null distribution.** Under the null that no particular IP is active, the count $n_a$ of appearances of IP address $a$ across candidate sets for all topic-username pairs follows a Poisson-binomial distribution:

$$\Pr(n_a = i) = \sum_{A \in F_i} \prod_{t \in A} q(k_t) \prod_{t' \in A^c} (1 - q(k_{t'}))$$

where $q(k_t) = 1 - \binom{2^{16}-1}{k_t}/\binom{2^{16}}{k_t}$ is the probability that IP $a$ appears in the candidate set for topic $t$ with $k_t$ observed usernames, and $F_i$ is the set of all size-$i$ subsets of topic indices.

**Test.** We compute the p-value $p_a$ for each IP address. If $p_a < p^*$ for some conservative threshold $p^*$, we declare the IP "active."

**Setting $p^*$ via placebo.** We calibrate $p^*$ empirically by repeating the entire procedure using positions 11–14 of the SHA-1 hash instead of the correct positions 10–13. This placebo set contains *only* noise. We set $p^*$ at the level that produces *zero* assignments under the placebo hash. The resulting thresholds — on the order of $10^{-11}$ for the 7-day window — naturally adjust for the approximately half-trillion hypothesis tests conducted simultaneously.

### 2.4 Assignment of Posts to IP Addresses

**Assignment procedure.** For each target day, we:
1. Collect all posts in a ±3-day window (7 days total).
2. Compute $n_a$ and $p_a$ for all IPv4 addresses.
3. Assign each post to the IP with the lowest p-value, *only* if that p-value is below $p^*$.

We repeat with 31-day and 91-day windows to capture less-frequent posters. We use position-9 assignments before July 8, 2013 and position-10 assignments afterward.

**Error analysis.** The number of false-positive assignments (posts assigned to IPs that never actually posted on EJMR) is in expectation less than one. A second error type — highly active IPs "stealing" assignments from true-posting IPs by chance — is estimated at ~0.2% for the most active IP address.

**Coverage.** We assign IP addresses to a majority of posts over the period spanning the site's history. Most assignments come from the 7-day window. Roughly speaking, if an IP address was the source of posts on more than about a dozen topics in a week, our method identifies it.

### 2.5 Linguistic Analysis

We analyzed the linguistic character of EJMR posts using transformer-based machine learning models. Posts first underwent preprocessing:

1. **Deobfuscation:** We developed a dictionary mapping common obfuscations (e.g., "f\*\*k," "secks," "fa//g//g//ot," leetspeak "d4mn j3ws") to canonical forms. Extensive obfuscation is used to evade EJMR's automated moderation.
2. **Language detection:** Posts were classified by language (English, German, Chinese, Korean, etc.) using the Lingua library (Stahl 2023).

**ML models:**
- **Toxicity:** ToxiGen Roberta (Hartvigsen et al. 2022), a RoBERTa checkpoint fine-tuned for toxicity — the same model used in Meta's LLaMA-2.
- **Misogyny:** Attanasio et al. (2022) fine-tuned BERT model.
- **Hate speech:** Barbieri et al. (2020) RoBERTa-based Twitter model.
- **Sentiment:** DistilBERT fine-tuned on Stanford Sentiment Treebank.
- **Validation:** Google's Perspective API (used by the New York Times, Wall Street Journal, and Financial Times) corroborates the toxicity results.

### 2.6 Comparison with Reddit

For comparison, we sampled 10,000 posts from each of the 1,000 most popular subreddits (with at least 10,000 posts in the Pushshift Reddit Dataset), and subjected them to the same linguistic analyses as EJMR posts.

### 2.7 Geolocation

We use the commercial IP2Location database to obtain country, city, latitude-longitude, zip code, ISP, and domain information. University IP addresses are identified by regex matching on ISP names.

### 2.8 Timestamps

EJMR does not display exact post times. We recover timestamps using:
1. The EJMR RSS feed (exact timestamps for ~10 most recent posts per topic), combined with WayBack Machine data — yielding exact timestamps for a large share of posts.
2. Linear interpolation based on auto-incrementing post IDs for the remaining posts. The average gap between posts with exact timestamps is about 3 minutes.

---

## 3. Results

### 3.1 Descriptive Statistics

Our data includes approximately **7 million posts** from roughly **642,000 topics** on EJMR between December 2010 and late April 2023. Some posts from registered users (who display non-hexadecimal usernames) are unassignable. From the assignable posts we recover tens of thousands of distinct IP addresses.

### 3.2 Time Patterns

**Overall trends.** Posting frequency steadily rose from December 2010 to April 2014, then stabilized at around 40,000 posts per month through 2019. In March 2020, posting jumped to ~70,000 posts per month with the onset of COVID-19 and remained elevated.

**COVID-19 effect.** The increase was driven entirely by the Off-Topic/Non-Econ forums, which quadrupled in size. The Economics forums showed a short transient increase that subsided within a year. In the United States, monthly posting volume tripled from ~10,000 to over 30,000 posts and remained high — unlike other countries (Canada, UK, Italy, France, Germany) where increases were more temporary.

**Job market cyclicality.** Job Market Rumors forum posts peak every December and January, reflecting the annual academic job market cycle.

**Time of day.** EJMR users post primarily during US work hours, regardless of year. Posts geolocated to non-US countries peak during the work and afternoon hours of their respective time zones.

**NBER Summer Institute.** Posts from the Royal Sonesta Boston — the conference hotel for the NBER Summer Institute — peak every July (when the invitation-only conference is held in person), with the exception of 2020 and 2021 when the conference was virtual.

### 3.3 Geographical Distribution

Among posts with geolocated IP addresses:
- **61.9%** originate from the **United States**
- **8.3%** from **Canada**
- **5.5%** from the **United Kingdom**
- Significant contributions from Australia, Germany, Hong Kong, Italy, France, and other countries with leading research institutions

**Cities.** The largest number of posts comes from Chicago, New York City, Hong Kong, Philadelphia, and Cambridge, MA — consistent with the geography of major economics departments. Cambridge (home of Harvard and MIT) ranks in the top five despite its small population. Smaller university cities like Berkeley also appear prominently.

**Universities.** 15.2% of all assigned posts originate directly from IP addresses associated with universities or research institutions. Posts from university IP addresses are found at *every* leading US university. The top 25 economics departments account for over 20% of all university posts worldwide. Among individual institutions, Stanford, Columbia, and the University of Chicago are the top three university contributors. The Federal Reserve Board — employing over 400 PhD economists — also appears prominently.

### 3.4 Concentration of Posters

Posting is highly concentrated:
- A mere **5%** of identified IP addresses generate **over 50%** of all assigned posts.
- **20%** of IP addresses generate **over 80%** of assigned posts.

This concentration follows a stretched exponential distribution (Guo et al. 2008; Lei et al. 2009). Fitting this distribution and extrapolating to the full IP space, we estimate that approximately **1.5 million IP addresses** have ever contributed at least one post to EJMR over the past decade. While the vast majority of posts come from a few thousand IP addresses, a very large number of IP addresses has contributed to the site.

### 3.5 University Self-Mentions

For the ten largest US university ISPs by post volume, posts from each university ISP most frequently mention their own institution (the diagonal in the self-mention table). Mentions of other universities tend to decline with institutional prestige. MIT stands out: posts from other university ISPs mention MIT almost four times more often than any other top-10 institution.

### 3.6 Content: Toxicity, Misogyny, and Hate Speech

**Overall shares.** Of all EJMR posts:
- **11.8%** are labeled **toxic** (ToxiGen Roberta)
- **3.3%** are labeled **misogynistic**
- **3.1%** are labeled **hate speech**

These shares have remained relatively constant since EJMR's inception, with mild seasonality (higher during summer months). The Off-Topic/Non-Econ forums have substantially higher rates of misogyny (~4%) and toxicity (~12%) than Economics (2%, 10%) or Job Market Rumors (2%, 8%) forums.

**Concentration.** 20% of identified IP addresses generate 81% of all toxic posts. Among the top 10 IP addresses by toxic post count, none are from university IPs. Among the top 10 university IPs by toxic post count, several are from leading institutions including the University of Chicago, the University of Rochester, the University of Washington, and University College London.

**EJMR versus Reddit.** Compared to the 1,000 most popular subreddits, EJMR posts rank at:
- **69th percentile** for misogyny
- **73rd percentile** for toxicity
- **95th percentile** for hate speech

EJMR has more posts labeled misogynistic, toxic, and hate speech than r/badeconomics, r/finance, and r/AskEconomics — the three most topically similar subreddits. For any given post length, EJMR posts are always more likely to be labeled as problematic than Reddit posts.

**University vs. non-university IPs.** Posts from university IPs are slightly less likely to be problematic (combined share ~11.8% vs. ~12.6% for non-university IPs). However, the share of posts that IPs contribute in *topics containing* at least one problematic post is identical across university and non-university IPs — with the average IP address having over 50% of its posts in topics that contain at least one toxic, misogynistic, or hate speech post.

**Gender targeting.** Posts mentioning women are substantially more likely to contain hate speech, misogyny, and toxicity than posts mentioning neither men nor women. Comparing the "women vs. neutral" gap to the "men vs. neutral" gap:
- On Reddit, mentions of women already trigger substantially more problematic content.
- On EJMR, this additional effect is *even larger* for misogyny and hate speech (though similar for general toxicity).

### 3.7 What Drives Posting Behavior?

**University-level predictors.** Using IPEDS data and RePeC rankings (2008–2022):
- US universities post ~25% more than non-US universities.
- Institutions with more economics students (undergraduate and graduate) have more posts.
- Higher-ranked universities post significantly more.
- Colleges without economics PhD programs post ~50% less.
- None of these characteristics significantly predict the *toxicity share* of posts.

**Attention and intrinsic motivation.** We examine whether attention drives posting, using an event-study design around the first time an IP creates a new topic:
- We measure the number of unique IPs responding in the first 24 hours (a proxy for attention received).
- We estimate how this initial attention affects the IP's posting activity on *other threads* over the next 30 days.

**Specification:**
$$y_{it} = \alpha_i + \alpha_t + \sum_{t,\, t \neq -7} \beta_t \cdot \text{Attention} + \epsilon_{it}$$

where $\alpha_i$ are IP fixed effects, $\alpha_t$ are event-time fixed effects, and "Attention" is the number of unique IPs in the initial topic within 24 hours.

**Results.** Each additional unit of attention on the initial post leads to:
- 0.125 more posts on the first day
- 0.40 more posts on the second day
- 0.25 more posts on the third day

This effect disappears by day 5 and is statistically indistinguishable from zero by that point. Importantly, this activity is in *other threads*, not the original topic. The ratio of toxic post effects (0.0125) to total post effects (0.15) implies ~8.3% toxic share, close to the overall EJMR average — suggesting attention does not disproportionately drive toxicity.

The attention effect is remarkable because EJMR users are completely anonymous with no persistent usernames. Unlike Reddit or TikTok (Srinivasan et al. 2023), EJMR users cannot build followings, accumulate status, or receive monetary payoffs from attention. The effect is driven purely by **intrinsic motivation** — the desire to see one's posts receive attention.

---

## 4. Conclusion

Using only publicly available data, we showed that the statistical properties of EJMR's username generation scheme (in use until May 2023) identify the IP addresses from which most posts were made. We recovered tens of thousands of distinct IP addresses, attributing them to a large majority of the roughly 7 million posts made over the past 12 years.

**What we found:**
- Posting on EJMR is geographically concentrated in major US and international cities with leading research institutions.
- 15% of posts come from university networks, including all top-ranked US universities — contradicting the common claim that EJMR is not representative of the economics profession.
- EJMR contains substantially more toxic, misogynistic, and hate speech content than anonymous internet forums in comparable settings.
- Problematic content is not limited to any particular subset of institutions and is widespread across the economics profession.
- Women are disproportionately targeted by hate speech and misogyny on EJMR, more so than on Reddit.
- Posting activity is concentrated among power users but extends to a very large estimated population of occasional contributors.
- Intrinsic attention-seeking — not reputational or monetary incentives — drives posting behavior in this fully anonymous environment.

Our paper provides further evidence of a toxic environment that is pervasive at all echelons of the economics profession, including, but not limited to, its most elite institutions.

---

## Appendix A: Alternative Toxicity Measures

We corroborate our main toxicity results using Google's Perspective API, which is used by the New York Times, Wall Street Journal, and Financial Times. The Perspective toxicity score represents the probability that a reader would perceive the comment as toxic. Under this definition, 20% of EJMR posts would be viewed as toxic by 25% of individuals, and 6% of posts would be viewed as toxic by 50% of individuals.

The correlation between ToxiGen Roberta toxicity and Perspective toxicity is 0.58, and the two measures imply very similar conclusions about the content of the site. The Wu (2018, 2020) word-count measures (sexual words, physical appearance words, negative intellectual words, swear words) are positively correlated with all three main classifiers.

## Appendix B: Frequently Asked Questions

**Is this a "hack"?** No. The study uses only publicly available EJMR pages — the same pages viewed by other EJMR users and indexed by search engines. No non-public pages, hidden URLs, or APIs were accessed.

**Did you abuse EJMR's servers?** No. The study used about 350,000 unique HTML pages, a small fraction of EJMR's traffic. We used a commercial web indexer that respects robots.txt and meters requests.

**Are you "doxing" people?** No. The paper does not identify persons. The single IP address disclosed was provided in response to a public million-dollar challenge issued by EJMR's owner.

## Appendix C: Posts by University ISP

The paper includes a comprehensive table of EJMR posts by university ISP for all universities with more than 100 posts, reporting the share of posts labeled toxic, misogynistic, and hate speech, positive and negative sentiment, and total post count. This table covers over 140 institutions from the United States and 30+ other countries.

Selected entries (institutions with >5,000 posts):

| Institution | Country | Combined | Toxicity | Hate Speech | Misogyny | Count |
|-------------|---------|----------|----------|-------------|----------|-------|
| HKUST | HK | 0.16 | 0.14 | 0.04 | 0.03 | 18,934 |
| University of Notre Dame | US | 0.12 | 0.09 | 0.02 | 0.03 | 18,498 |
| Stanford University | US | 0.09 | 0.08 | 0.01 | 0.02 | 17,813 |
| Columbia University | US | 0.10 | 0.08 | 0.02 | 0.02 | 14,970 |
| University of Chicago | US | 0.13 | 0.11 | 0.02 | 0.03 | 14,597 |
| University of Washington | US | 0.13 | 0.12 | 0.02 | 0.02 | 11,089 |
| University of Michigan | US | 0.11 | 0.09 | 0.02 | 0.03 | 10,734 |
| Pennsylvania State University | US | 0.08 | 0.06 | 0.01 | 0.02 | 10,723 |
| University of Rochester | US | 0.17 | 0.16 | 0.04 | 0.02 | 9,802 |
| University of Oxford | GB | 0.09 | 0.08 | 0.02 | 0.02 | 9,296 |
| UC Berkeley | US | 0.12 | 0.09 | 0.04 | 0.01 | 8,784 |
| Federal Reserve Board | US | 0.07 | 0.05 | 0.01 | 0.01 | 6,720 |
| Northwestern University | US | 0.09 | 0.07 | 0.02 | 0.02 | 5,760 |
| University of Cambridge | GB | 0.10 | 0.09 | 0.02 | 0.02 | 5,738 |
| UC Los Angeles | US | 0.15 | 0.14 | 0.06 | 0.02 | 2,368 |
| Harvard University | US | 0.10 | 0.09 | 0.01 | 0.02 | 3,653 |
| Yale University | US | 0.14 | 0.12 | 0.03 | 0.03 | 3,749 |
| London School of Economics | GB | 0.10 | 0.08 | 0.02 | 0.03 | 3,826 |
| Princeton University | US | 0.11 | 0.10 | 0.02 | 0.02 | 5,029 |
| New York University | US | 0.09 | 0.08 | 0.02 | 0.02 | 2,280 |
| International Monetary Fund | US | 0.14 | 0.12 | 0.03 | 0.03 | 1,495 |
| World Bank Group | US | 0.07 | 0.05 | 0.01 | 0.02 | 3,894 |
