# Anonymous Attention and Abuse

**Florian Ederer** (Boston University, CEPR, ECGI, and NBER)
**Paul Goldsmith-Pinkham** (Yale University; NBER)
**Kyle Jensen** (Yale University)

*AEA Papers & Proceedings*, Vol. 115, pp. 188–194, May 2025

---

Economics Job Market Rumors (EJMR) occupies a controversial position within the economics profession. While it began as an anonymous forum primarily focused on the annual job market for economics PhDs, its scope has expanded significantly over the years. Today, EJMR serves as both a clearinghouse for job market information and a breeding ground for discussions that range from professional commentary to abusive rhetoric. The forum is infamous for hosting content that is defamatory, misogynistic, and otherwise toxic. Its anonymity fosters candid discussions, but it also enables behaviors that contribute to its notoriety. This duality — as both a valuable resource and a harmful platform — raises important questions about its role in the economics community.

The influence of the platform is considerable. In early 2023, SimilarWeb estimated that EJMR received 2.5 million monthly visits, surpassing even prominent academic resources such as the National Bureau of Economic Research (NBER) and the American Economic Association (AEA) websites in terms of page views per visit. Despite its popularity, EJMR has been criticized as a "cesspool of misogyny" (David Romer), "4chan for economists," and evidence of a toxic culture that marginalizes women and underrepresented groups within the profession.

This paper analyzes EJMR content from January 2012 to May 2023 — the sample ends when the public announcement of the results of Ederer, Goldsmith-Pinkham, and Jensen (2024) significantly changed the content and discourse on EJMR — and focuses on three key aspects: (1) the prevalence and impact of links to external domains; (2) the surge in discussions driven by Twitter posts since 2018; and (3) the categorization of individuals whose tweets and content are discussed on EJMR.

---

## I. Links to External Domains

From January 2012 to May 2023, the proportion of EJMR topics containing a link in the first post varies between roughly 10 and 20 percent. To measure links, the paper uses a database of all posts on EJMR and identifies all links (anchor tags with href attributes in HTML), rolling them up to their canonical domain name (e.g., combining m.twitter.com and www.twitter.com into the Twitter domain). The analysis focuses on links in the first post of a given topic to avoid double counting.

**Early period:** At the beginning of the sample, approximately 10 percent of opening posts contain links to YouTube. Beginning in 2018, YouTube links disappear almost entirely due to automatic moderation instituted on EJMR, which substantially reduced the ability to post links to YouTube as such posts increasingly contained repetitive spam.

**Mid-sample (2018–2020):** About 5 percent of topics link to economic research sources such as Marginal Revolution (a popular economics blog), the NBER, and to a much lesser extent the economics working paper repository RePEC. The remaining 5 percent link to Twitter, Wikipedia, the New York Times (with a large share linking to Paul Krugman's contributions), the Guardian, and other EJMR topics. Links to Marginal Revolution are overwhelmingly posted by a specifically designed bot. Links to NBER are mostly to new NBER working papers (96.3%), with a small share to conference schedules posted by human users.

**Since 2018:** EJMR experienced a substantial increase in topics initiated by references to Twitter posts. The proportion of EJMR topics citing Twitter surged from around 1% in 2018 to nearly 8% by 2023. This shift mirrors Twitter's growing importance as a real-time source of information in academic and public policy circles — the rise of #EconTwitter. Simultaneously, the share of topics linking to Marginal Revolution and the NBER fell precipitously after 2020 and 2021 respectively, almost entirely displaced by the increase in Twitter links. By 2022, almost 8,000 EJMR topics per year opened with a link to Twitter.

---

## II. Referenced Twitter Accounts on EJMR

Given the rise of Twitter on EJMR, the paper identifies which Twitter accounts receive the most attention. For each of the most-frequently-linked accounts, the account's name, description, and most recent tweets were retrieved and fed to OpenAI's GPT-4o for a five-to-ten-word classification of the account owner. The paper also reports z-scores of the average post classification measures — Hate Speech, Negativity, Misogynistic, and Toxic — from Ederer, Goldsmith-Pinkham, and Jensen (2024) for the opening posts of EJMR topics linking to each account. A z-score of 1 reflects one standard deviation above the average across all linked Twitter users; red indicates high z-scores and blue indicates low z-scores.

### Top 50 Most-Mentioned Twitter Accounts

The most frequently mentioned accounts (with number of topics) are:

| Twitter Username | LLM Description | Topics |
|---|---|---|
| realChrisBrunet | Right-wing commentator and controversial social media figure | 325 |
| elonmusk | Billionaire entrepreneur and technology influencer | 302 |
| RichardHanania | Conservative commentator and president of policy center | 189 |
| Claudia_Sahm | Economist and expert on fiscal policy and Fed | 172 |
| jenniferdoleac | Economist and criminal justice policy expert | 162 |
| Noahpinion | Economics blogger and commentator with a humorous style | 158 |
| JustinWolfers | Economics professor and commentator on public policy | 132 |
| libsoftiktok | Conservative social media commentator and agitator | 105 |
| visegrad24 | Conservative news aggregator and commentator on current affairs | 103 |
| realDonaldTrump | Former U.S. President and conservative political figure | 102 |
| disclosetv | Sensationalist news aggregator with a conservative slant | 92 |
| nntaleb | Philosopher and author focused on probability and society | 91 |
| paulkrugman | Nobel prize winning economist and columnist | 86 |
| mattyglesias | Political commentator and journalist | 84 |
| Steve_Sailer | Conservative commentator and social critic | 76 |
| florianederer | Economics professor with interest in antitrust and policy | 40 |

*(Additional accounts include zerohedge, realchrisrufo, MrAndyNgo, nytimes, DrEricDing, arindube, ProfEmilyOster, haralduhlig, and others; two accounts marked with * have been anonymized per the account holders' wishes.)*

### Three Groups of Accounts

The most-referenced accounts fall into three main groups:

1. **Economists** (e.g., Claudia_Sahm, jenniferdoleac, JustinWolfers): Academic and professional economists whose tweets often serve as springboards for debates on research findings, policy implications, and professional conduct.

2. **Right-wing commentators and agitators** (e.g., realChrisBrunet, RichardHanania, libsoftiktok): Reflects EJMR's right-wing slant and engagement with contentious political and social issues.

3. **News sources and journalistic accounts**, many with a conservative slant (e.g., visegrad24, disclosetv, nypost).

### Toxicity of Discussions Referencing Female Economists

Among the 10 most frequently mentioned Twitter accounts there are four economists, including three female economists. EJMR posts referencing two of these female economists have very high average misogyny z-scores:

- **Claudia_Sahm:** Misogynistic z-score = 1.974
- **jenniferdoleac:** Misogynistic z-score = 2.598

These results are particularly stark examples of the systematic finding that EJMR posters discuss female economists in strongly misogynistic terms compared to all other Twitter accounts mentioned on EJMR. The only other large misogyny z-score is for **elben** (Misogynistic z-score = 0.956), an academic economist who championed LGBTQ-inclusive policies in the economics profession.

Several other prominent economists are also discussed in negative or toxic terms: ProfEmilyOster (Negativity z-score = 0.433), arindube (Toxic z-score = 1.009), and DrEricDing (Hate Speech z-score = 1.014). Note: Two accounts with extremely positive sentiment (large negative Negativity z-scores) are referenced by repetitive spam posts on EJMR containing Christian messages of love and forgiveness.

---

## Conclusion

EJMR's trajectory — marked by increased linkage to social media and broadening external references — underscores the forum's dual role as an information aggregator and a mirror of professional economics. EJMR's toxic culture raises concerns about inclusivity and the amplification of divisive narratives. Addressing these challenges requires a concerted effort to balance the platform's informational utility with its broader impact on the economics profession.
