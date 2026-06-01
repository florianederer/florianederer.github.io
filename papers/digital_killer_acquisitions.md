# Digital (Killer?) Acquisitions

**Authors:** Florian Ederer (Boston University; CEPR, ECGI, and NBER), Regina Seibel (Toronto Rotman School of Management), Timothy Simcoe (Boston University Questrom School of Business and NBER)

**Status:** Working Paper

**JEL Codes:** L41 (Monopolization; Horizontal Anticompetitive Practices), O31 (Innovation and Invention: Processes and Incentives), O34 (Intellectual Property and Intellectual Capital)

**Keywords:** Innovation, Acquisitions, Patents

---

## Abstract

This paper examines the effects of 1,200 acquisitions by major technology firms on innovation. Using detailed patent and workforce data linked to technology acquisitions and a suite of event-study and difference-in-differences designs, we document four main findings. First, although most acquired startups hold no patents, those with patents tend to operate in technology areas where the acquirer already has a presence and which subsequently experience further acquisition activity. Second, innovation typically rises before an acquisition but only persists afterward when further acquisitions occur, suggesting that acquisitions respond to innovation trends rather than initiating them. Third, at the patent level, acquired patents receive significantly more citations after the acquisition than comparable patents, and these effects are not driven solely by self-citations from the acquiring firm. These post-acquisition citation effects are smaller when more employees from the acquired firm are retained, consistent with innovation spillovers occurring through employee mobility. Fourth, we document significant workforce attrition exceeding 50% on average at target firms three years post-acquisition. Our results suggest that acquisitions by digital incumbents often amplify, rather than suppress, the diffusion and visibility of acquired technologies.

---

## 1. Introduction

The rising dominance of large digital platforms has sparked renewed interest in the competitive implications of their acquisition behavior. Over the past two decades, leading technology firms — including Amazon, Apple, Facebook, Google, and Microsoft (commonly referred to as GAFAM) — as well as Cisco, Intel, and Qualcomm have each engaged in hundreds of acquisitions, often targeting early-stage startups in adjacent or emerging technology markets. These transactions raise important questions about how markets for technology function, and whether acquisitions facilitate or hinder the commercialization and diffusion of innovative ideas.

Given the complementary assets required to bring new technologies to market, innovative startups often rely on licensing deals or acquisitions to appropriate returns from their inventions. At the same time, regulators, policymakers, and scholars have raised concerns that some of these acquisitions may serve anticompetitive purposes. A growing body of research emphasizes innovation-based theories of harm, highlighting that mergers can reduce innovation incentives, eliminate nascent competition, or alter the direction of technological progress. These concerns are particularly salient in digital markets, where acquisitions can affect not only current competition but also the trajectory of future innovation. Recent policy discussions and interventions, including the 2023 U.S. Merger Guidelines and the EU Digital Markets Act, explicitly recognize that repeated or serial acquisitions may cumulatively undermine competitive innovation dynamics.

This paper investigates the effects of startup acquisitions by major digital incumbents on subsequent innovation outcomes within narrowly defined technological domains. Rather than focusing on the ex-ante incentives of potential acquisition targets — a common emphasis in the theoretical literature — we examine ex-post outcomes using an event-study framework. Specifically, we analyze changes in patenting and patent citations before and after an acquisition, thereby assessing how these deals reshape the trajectory of innovation in the affected technology space.

**Three main contributions.** First, we provide a comprehensive empirical mapping of the acquisition behavior of eight major digital firms (the GAFAM firms plus Cisco, Intel, and Qualcomm). We manually compile a dataset of 1,200 acquisitions and link this information to patent data from PatentsView and labor market data from Revelio Labs. We show that while these firms have acquired a large number of startups, the majority of targets do not hold patents at the time of acquisition, which suggests that many deals are motivated by access to capabilities, products, customers, or personnel rather than formal intellectual property. We also find that while retention rates vary substantially across deals, on average, only 45% of target firm employees remain at the acquirer three years after the acquisition, highlighting the fragility of workforce integration.

We find that acquisitions are highly concentrated in specific technological domains and often represent repeated engagement by the same acquirer in a given area. Hardware-focused firms such as Intel and Qualcomm tend to acquire targets in Cooperative Patent Classification (CPC) categories where they already hold patents, suggesting a form of cumulative innovation or vertical integration. In contrast, software-oriented firms such as Facebook or Amazon are more likely to pursue acquisitions without patents, perhaps reflecting a focus on user bases, engineering talent, or data assets.

Second, we construct a panel dataset at the technology-class-year level that allows us to analyze innovation trends surrounding each deal. We find that innovation frequently precedes acquisition — a finding that undermines the killer acquisition narrative in its strongest form, where the incumbent preemptively shuts down nascent rivals. Instead, many acquisitions follow a surge of patenting within the same CPC groups where the acquired startup operates, consistent with incumbents acquiring startups to access promising technologies.

Using event-study and difference-in-differences analyses, we estimate that patenting activity in affected CPC groups generally continues to rise after an acquisition. However, the post-acquisition growth in patenting is only present when follow-on acquisitions occur in the same technology space. This provides complementary evidence on acquisition rollups and speaks directly to the evolving regulatory framework that assesses mergers occurring as part of a pattern or strategy collectively rather than in isolation.

Third, we examine the effects of acquisitions at the level of individual patents. Using a difference-in-differences framework, we show that acquired patents receive significantly more citations after the acquisition than comparable patents in the same CPC group. These effects are not limited to citations from the acquiring firm but extend to third-party citations, suggesting that acquisitions increase the visibility and influence of acquired technologies across the broader technology ecosystem. The post-acquisition citation boost is especially pronounced for first-acquired targets in CPC groups that experience follow-on acquisitions. We also find that post-acquisition citation effects are significantly smaller when a larger share of the workforce is retained — consistent with innovation spillovers being driven in part by departing employees who disseminate knowledge beyond the acquiring firm.

Our findings complicate the popular narrative that digital acquisitions by large incumbents are predominantly anti-competitive. While we do not rule out the possibility of killer acquisitions in individual cases, our evidence suggests that most deals by GAFAM and related firms are motivated by complementarity rather than suppression. Innovation tends to rise rather than fall in the wake of acquisition, particularly in technological domains where the acquirer has prior experience and continues to make follow-on investments.

---

## 2. Simple Model

This section develops a model of startup acquisitions in a technology space with uncertain commercial viability. Beliefs about viability evolve through Bayesian updating on public signals, generating an equilibrium in which acquisitions and innovation co-move with beliefs. The model makes the following predictions: (i) the clustering of acquisitions into waves, sustained by positive feedback between beliefs and entry; (ii) a pre-acquisition rise in innovation activity in spaces that go on to be acquired, reflecting selection across technology states; (iii) a persistent reduction in innovation after acquisition waves, driven by the incumbent's accumulated competitive presence; and (iv) the emergence of *killer acquisitions* — acquisitions in which the incumbent shelves rather than commercializes the target's project — in periods when preventing standalone entry is worth more to the incumbent than the entrant's own standalone value. Predictions (i)–(iii) are consistent with the empirical patterns we document; prediction (iv) is an implication of the model that we do not test directly.

### 2.1 Setup

**Players and state.** Consider a single technology space. Time is discrete, $t = 1, 2, \ldots$. There is one incumbent platform firm and one potential entrant per period (short-lived: present for one period only). The space has an unknown *commercial viability* state $\theta \in \{H, L\}$, with prior $\mu_0 \equiv \Pr(\theta = H) \in (0,1)$. A project with technical quality $x$ has commercial value $x$ if $\theta = H$ and zero if $\theta = L$.

**Timing.** Let $N_t$ denote the cumulative number of acquisitions before period $t$. Each period proceeds as follows: (1) A public signal $s_t \in \{h, \ell\}$ about $\theta$ is drawn and all participants update beliefs to $\mu_t$ via Bayes' rule. (2) The entrant draws project quality $x_t \geq 0$ from distribution $F$. (3) The entrant decides whether to develop at cost $c > 0$. (4) Whether development occurred, and if so the quality, become public; if the entrant developed, the incumbent may acquire the project.

**Belief updating.** Given prior belief $\mu_{t-1}$, Bayes' rule gives:

$$\mu_t = \begin{cases} \dfrac{q_H\,\mu_{t-1}}{q_H\,\mu_{t-1} + q_L(1-\mu_{t-1})} > \mu_{t-1} & \text{if } s_t = h \\[10pt] \dfrac{(1-q_H)\,\mu_{t-1}}{(1-q_H)\,\mu_{t-1} + (1-q_L)(1-\mu_{t-1})} < \mu_{t-1} & \text{if } s_t = \ell \end{cases}$$

where $q_H > q_L$ are the signal precisions under $H$ and $L$ respectively.

**Project values.** Commercialization yields $\mu_t \cdot \kappa(N_t) \cdot x$, where $\kappa(N_t)$ is the *commercialization advantage* with $\kappa(0) > 1$. If the entrant operates independently, it receives standalone value $\mu_t \cdot \gamma(N_t) \cdot x$, where $\gamma$ captures *competitive crowding* with $\gamma(0) = 1$ and $\gamma$ non-increasing in $N$. Standalone entry also imposes a *competitive externality* $\mu_t \cdot D(N_t) \cdot x$ on the incumbent.

**Payoffs.** The incumbent makes a take-it-or-leave-it offer at price $P_t = \mu_t \gamma(N_t) x_t$, matching the entrant's standalone payoff. The incumbent's acquisition surplus is:

$$S_t = \max(S_t^C,\; S_t^S,\; 0)$$

with $S_t^C \equiv \mu_t x_t [\kappa(N_t) + D(N_t) - \gamma(N_t)] - d_I$ (commercialization surplus) and $S_t^S \equiv \mu_t x_t [D(N_t) - \gamma(N_t)]$ (shelving surplus). Three regimes partition the parameter space:

- *Pre-emption regime*: $D(N_t) > \gamma(N_t)$. The incumbent acquires every developed project, commercializing those with $x_t \geq d_I / (\mu_t \kappa(N_t))$ and shelving the rest. The shelved deals constitute **killer acquisitions**.
- *Commercialization regime*: $D(N_t) \leq \gamma(N_t)$ and $\kappa(N_t) + D(N_t) > \gamma(N_t)$. The incumbent acquires only high-quality projects and commercializes all of them.
- *No-acquisition regime*: $\kappa(N_t) + D(N_t) \leq \gamma(N_t)$. No acquisitions occur.

**Entry condition.** The entrant develops if and only if:

$$x_t \geq \underline{x}(\mu_t, N_t) \equiv \frac{c}{\mu_t \, \gamma(N_t)}$$

This threshold is strictly decreasing in $\mu_t$ and weakly increasing in $N_t$.

### 2.2 Results

**Proposition 1 (Positive feedback).** For fixed $(N_t, \theta)$, $\Pr(a_t = 1 \mid \mu_{t-1})$ is increasing in $\mu_{t-1}$.

*Proof.* Higher $\mu_{t-1}$ implies higher $\mu_t^h$ and $\mu_t^\ell$ (Bayes' rule is monotone), which lowers the entry threshold $\underline{x}$, so the acquisition probability rises.

**Proposition 2 (Pre-acquisition rise).** Conditional on an acquisition occurring at date $\tau$, $\Pr(\theta = H \mid a_\tau = 1) > \Pr(\theta = H)$; and under $\theta = H$, expected beliefs drift upward. Consequently the expected development probability, conditional on a future acquisition, is weakly increasing in $t$ before $\tau$.

**Proposition 3 (Post-wave moat).** The entry threshold $\underline{x}(\mu_t, N_t) = c / [\mu_t \gamma(N_t)]$ is weakly increasing in $N_t$. Once acquisitions cease at $T^*$, $N_t$ freezes at $N_{T^*}$ and the elevated threshold persists indefinitely.

*Implication.* The incumbent's moat is larger after longer waves: more acquisitions mean lower $\gamma$. Post-wave innovation is persistently below the pre-wave level, with the gap widening in the size of the wave.

**Proposition 4 (Pre-emption and killer acquisitions).** In any period with $D(N_t) > \gamma(N_t)$:
- (i) the incumbent acquires every developed project;
- (ii) projects with $x_t < d_I / (\mu_t \kappa(N_t))$ are shelved rather than commercialized — these are killer acquisitions;
- (iii) if $\kappa(N_t)$ is decreasing in $N_t$, the share of acquired projects that are killer acquisitions rises with $N_t$.

### 2.3 Discussion

The model produces two distinct senses in which technology spaces dominated by the incumbent are hostile to standalone innovation. The first is a passive byproduct of the wave: accumulated competitive crowding raises the independent-development threshold both during and after the wave. The second is direct: in the pre-emption phase, the incumbent acquires every developed project, shelving the lower-quality ones outright as killer acquisitions.

---

## 3. Data

### 3.1 Acquisition Data

We assemble a manually curated dataset of startup acquisitions by eight prominent technology companies: Amazon, Apple, Cisco, Facebook, Google, Intel, Microsoft, and Qualcomm. We selected these firms due to their longstanding presence in digital and information technology sectors, their high frequency of acquisition activity, and their central role in debates on digital competition and innovation policy.

For each acquisition, we record the name of the acquired company, the year of acquisition, and, where available, information about the target's patenting activity and deal value. In order to focus on startup acquisitions, we exclude large deals involving targets with extensive patent portfolios (such as Apple's acquisition of Intel's modem business). We identify 1,190 acquisitions of emerging innovators, comprising the vast majority of all acquisitions by the eight firms. We link each acquired startup to its patent portfolio using name-based matches between targets and assignees in U.S. patent data.

### 3.2 Patent Data

To characterize technological activity, we rely on data from the PatentsView database. We extract patent filings and grants, including application years, Cooperative Patent Classification (CPC) codes, and assignee information. The CPC system is a hierarchical classification system devised by the USPTO and European Patent Office, designed to facilitate prior art searches. We focus on patents in CPC sections G (Physics) and H (Electricity), which encompass 1,289 CPC classes covering the majority of innovation activity in information technology, software, electronics, and telecommunications.

We use the six-digit main group associated with a patent's primary CPC code as that patent's "CPC class." This provides granular, economically meaningful technological categories while keeping the number of classification units computationally tractable.

### 3.3 Data on Employee Work Histories

We use data from Revelio Labs to analyze employee-level career trajectories before and after acquisition events. Revelio Labs aggregates publicly available resumes, primarily from LinkedIn, to construct standardized longitudinal records of individuals' employment histories.

We limit the sample to acquisitions occurring in 2005 or later (since LinkedIn was founded in 2003), yielding 932 acquisitions, of which we cleanly identify and verify 606 targets in the Revelio data. We identify the acquiring firms in the Revelio data inclusive of all affiliated subsidiaries — for instance, positions at Instagram, DeepMind, or GitHub are treated as positions at Facebook, Google, and Microsoft, respectively, after their respective acquisition dates.

### 3.4 Dataset Construction

Our empirical analysis uses two panel datasets. In the first, each observation represents a unique technological field (CPC class) in a specific year. For each CPC-year combination, we calculate the number of patent applications filed, identify whether an acquisition occurred involving a target firm that had previously patented in that CPC group, and record which of the eight focal technology firms carried out the acquisition.

In the second panel, each observation represents a single patent in a given year. We restrict the sample to patents in CPC groups containing at least one patent filed by a target firm before its acquisition, and track whether each patent was filed by the acquired firm or a third party. Our main outcome variable is the number of forward citations a focal patent receives from other U.S. patents filed or granted in a particular year — a widely used measure of the economic and technological significance of the cited patent.

---

## 4. Descriptive Statistics

### 4.1 Big Tech Acquisitions

Across all eight acquirers, a substantial share of startup targets do not hold any patents at the time of acquisition. The probability that an acquired firm holds at least one patent ranges from as low as 17% for Facebook to as high as 70% for Qualcomm. This heterogeneity reflects differences in acquisition strategies: semiconductor and hardware-intensive firms (Intel, Qualcomm) place greater emphasis on acquiring patented technologies, while software-oriented firms (Facebook, Amazon) more often target capabilities, user bases, or engineering talent.

Conditional on acquiring a patent-holding target, the average number of patents also varies substantially. Intel and Qualcomm stand out with average target portfolios exceeding 20 patents per acquisition; targets acquired by Facebook and Amazon typically have smaller patent portfolios. The data also reveal a clear patent premium in deal valuation: across nearly all firms, acquisitions of patent-holding targets are associated with substantially larger transaction values. For instance, Apple paid roughly eight times more for the median patent-holding target ($239 million) than for the median target without patents ($30 million). Similarly, Google's median deal size increases from $61 million to $500 million when the target holds patents.

On average, only about 50% of target firm employees remain at the acquirer three years after the merger, and roughly one-third remain after five years. The "Retention Gap" — the difference in retention between target employees and a matched sample of existing acquirer employees with similar tenure — varies substantially across acquirers, suggesting meaningful differences in post-acquisition integration practices.

Acquisition activity is unevenly distributed over time, with noticeable peaks in certain years. There is a pronounced increase in acquisition activity during the early 2010s, corresponding to a period of aggressive growth by firms like Google, Facebook, and Amazon.

### 4.2 Acquired Patent CPC Codes

Restricting to 1,289 CPC codes within sections G and H, a total of 303 distinct G&H CPC codes are affected by at least one acquisition. Among these treated CPC groups, approximately 38% experience only a single acquisition event, while the remaining 62% are treated multiple times, reflecting repeated acquisition activity within the same technological field.

Acquirers frequently enter CPC groups where they already have a foundation of prior patenting activity. Intel already owned patents in 167 out of 177 CPC classes it "entered" through acquisition, and Microsoft had prior patents in 98 of 103 cases. Even for software and platform firms like Google and Apple, there is a strong tendency to acquire in domains where they already hold intellectual property.

### 4.3 Repeat Acquisitions

Many CPC groups experience multiple acquisition events, and acquisition waves are often concentrated in short time intervals: more than 50% of events in the any-acquirer panel are followed by another deal within one year, and roughly 70% within two years. When an acquirer had previously patented in a CPC group before its first acquisition there, 90% of first acquisitions are followed by additional acquisitions in that group. By contrast, when the acquirer has no prior experience in a CPC group, the first acquisition is much more likely to be an isolated event.

The share of patents owned by the eight large acquirers increases with cumulative acquisitions in a CPC group, reflecting consolidation through both organic patenting and acquisition of patents previously held by targets. IP ownership becomes more concentrated in the hands of big tech in CPC groups associated with larger acquisition waves.

### 4.4 Employee Retention

Target employees experience a steep drop in retention in the first year after a deal, with almost 40% leaving their employer within a year. By three years after the acquisition, cumulative attrition exceeds 50%. In contrast, matched acquirer employees display a substantially flatter retention curve over the same time window. This pattern is broadly consistent across all eight acquiring firms, though with some variation in level and slope of post-acquisition attrition.

---

## 5. Results

### 5.1 CPC Group Level Analysis

#### 5.1.1 Baseline Event Study

Our primary outcome variable, $lpat_{ct}$, is the arcsin transformation of the total number of patents filed in CPC class $c$ in year $t$. The baseline event-study specification is:

$$lpat_{ct} = \alpha + \gamma_c + \lambda_t + \sum_{s=-10}^{10} \tau_s \times d_{c,t=y+s} + \epsilon_{ct}$$

where $\gamma_c$ are CPC group fixed effects, $\lambda_t$ are calendar-year fixed effects, and $d_{c,t=y+s}$ indicates that CPC group $c$ experienced an acquisition $s$ years ago. The coefficients $\tau_s$ — dynamic treatment effects — capture the percentage change in patent filings relative to the baseline year ($s = -1$).

The baseline results reveal a marked upward trend in patenting before the acquisition, followed by continued growth afterward. Disaggregating by the number of follow-on acquisitions shows that the pre-acquisition growth in patent filings continues if and only if there are follow-on acquisitions in the treated CPC group: when there are more follow-on acquisitions, the post-first-acquisition growth in patenting is larger, and patenting declines in treated CPC codes that see no further acquisition activity.

Both the common and heterogeneous-trend specifications reveal strong pre-trends, indicating that acquisitions are not randomly assigned across CPC groups but are more likely to occur in areas with accelerating innovation.

#### 5.1.2 Event Study with Matched Controls

To address the pre-trend concern, we construct a more comparable control group using nearest-neighbor matching based on pre-acquisition patent growth, number of patent applications, and the acquisition year. The matching procedure effectively balances pre-treatment trends. As expected, the use of matched control groups eliminates the strong pre-trends observed in the unmatched analysis.

Post-acquisition, the matched results show clear heterogeneity: CPC groups with multiple follow-on acquisitions experience significantly larger increases in patenting, while CPC groups with only a single acquisition show no statistically significant change in the number of patents filed.

Crucially, running the same event-study design using the *last* acquisition event within a CPC group as the main treatment event shows no post-treatment increase in patenting relative to matched controls. This provides further evidence that follow-on acquisitions are not merely coincidental — the post-acquisition patenting boost occurs before the last acquisition and is not attributable to the terminal deal alone.

Overall, the evidence shows that growth in patenting precedes the first startup acquisition in a CPC, and this growth continues if and only if there are follow-on acquisitions in the same CPC. This pattern is consistent with models where innovation responds to expectations about exit or commercialization opportunities.

### 5.2 Patent Citation Analysis

#### 5.2.1 Impact of Acquisitions on Acquired Patents

We analyze how the citation rate to acquired patents changes following acquisitions using three specifications:

$$cit_{pct} = \alpha + \tau \cdot PostAcquisition_{pt} + Acquired_p + i.age_{pt} + \lambda_{ct} + \epsilon_{pct}$$

$$cit_{pct} = \alpha + \tau \cdot PostAcquisition_{pt} + age_{pt}^2 + age_{pt}^3 + \gamma_p + \lambda_{ct} + \epsilon_{pct}$$

$$cit_{pct} = \alpha + \sum_{s=-10}^{10} \tau_s \cdot d_{p,t=y+s} + age_{pt}^2 + age_{pt}^3 + \gamma_p + \lambda_{ct} + \epsilon_{pct}$$

where $\gamma_p$ are patent fixed effects and $\lambda_{ct}$ are CPC-group by year fixed effects.

The key variable of interest, $PostAcquisition_{pt}$, is a dummy equal to one in all years after the acquisition of the patent's parent firm. The coefficient is positive and highly significant: the post-acquisition effect is approximately **1.10 additional citations per year**, corresponding to a **138% increase** in the mean citation rate. The coefficient on $Acquired_p$ indicates that acquired patents have a 67% higher citation rate than other patents in the same CPC classes *before* the acquisition, confirming that acquirers select higher-quality targets. In the patent fixed effects specification, the main treatment effect remains essentially unchanged.

On citation timing: assigning forward citations to the grant year (rather than the conventional application year) eliminates the modest pre-trend visible in the event-study graphs and produces a cleaner identification. This is consistent with the idea that some "in-process" citations — added during patent examination — may be causally attributable to the acquisition itself.

#### 5.2.2 Heterogeneity by Acquisition Sequence

Patents owned by first-acquired targets in CPC groups that subsequently experience additional acquisitions show a particularly strong post-acquisition increase in citations. In contrast, patents associated with isolated acquisitions (those not followed by further deals) show smaller or insignificant citation effects. Later-acquired targets exhibit positive post-acquisition citation effects, though generally smaller in magnitude compared to first-acquired firms in multi-acquisition CPC groups.

These findings suggest that the strategic sequencing of acquisitions matters for innovation outcomes. First acquisitions in an area that becomes the focus of sustained follow-on activity appear to generate the strongest citation-based spillovers.

#### 5.2.3 Mechanisms: Self-Citations vs. External Spillovers

A sharp rise in self-citations from the acquiring firm begins immediately after the acquisition, suggesting that acquiring firms intensify their reuse or integration of acquired technologies. However, after excluding all citations from the acquiring firm, a strong and sustained post-acquisition increase in citations remains. The estimated effect is approximately **0.85 citations per year** from non-acquirers, down from 1.13 in the full baseline. This confirms that the observed citation effects are not exclusively driven by self-citations and reflect genuine external spillovers.

When citations are aggregated at the patent family level (to account for related patents covering the same underlying invention), the post-acquisition citation boost remains positive and statistically significant at approximately 0.43 citations per year. These alternative specifications reinforce the core finding that acquisitions increase the broader visibility and diffusion of acquired patents.

### 5.3 Employee Retention and Citations

To explore the link between post-acquisition workforce integration and citation impact, we interact the post-acquisition treatment indicator with the (demeaned) share of target employees still employed at the acquirer three years after the deal.

The interaction between the post-acquisition indicator and the demeaned retention rate is **negative and statistically significant** (approximately −0.97 in the CPC-year FE specification and −0.68 with patent FE). These coefficients imply that the citation boost from acquisition is smaller in deals with higher employee retention.

One plausible interpretation is that when retention is low, departing employees disseminate knowledge externally by joining or founding other firms, leading to broader diffusion and more citations. Conversely, when more of the workforce is retained, innovations may remain embedded within the acquiring firm, limiting external visibility. In more colloquial terms, a successful acqui-hire may be bad news for knowledge spillovers. This mechanism is consistent with the role of employee mobility in spreading knowledge in high-tech labor markets.

---

## 6. Conclusion

Using a novel dataset linking over 1,000 startup acquisitions by eight large technology firms to detailed patent-level information, we implement an event-study framework to trace changes in both the quantity and quality of innovation before and after acquisition events.

Our results offer a nuanced view of the killer acquisition narrative. We find little evidence that acquisitions by large digital firms suppress innovation. On the contrary, patenting activity tends to increase in CPC groups following an acquisition, especially when there are follow-on acquisitions in the same domain. Matched control group comparisons confirm that this pattern is not driven by differential pre-trends. Citation-based analyses reinforce these findings: patents owned by acquired firms receive significantly more citations after the acquisition, and this increase extends to external innovators — suggesting broader knowledge diffusion rather than internal hoarding.

We document important heterogeneity. The strongest post-acquisition innovation responses occur when the acquirer had prior patenting experience in the CPC group and when the acquisition is followed by additional deals in the same domain. First acquisitions in these acquisition waves show especially large increases in citations. Robustness checks using grant-year citations and patent family aggregations confirm the reliability of our results.

From a policy perspective, our findings suggest that many acquisitions by digital incumbents are motivated by complementarity rather than suppression. While this does not rule out the existence of killer acquisitions in specific cases, the evidence indicates that, on average, these deals promote rather than stifle technological progress. These insights have implications for merger review in digital markets, where blanket skepticism may overlook the potential for innovation-enhancing firm integration.

---

## Appendix

### A.1 Citation Analysis Structure

The distribution of treated patents by event time (years before or after the acquisition of their parent firm) is roughly symmetric around the acquisition year, with a notable concentration of observations in the period spanning five years before to five years after acquisition. The drop-off in observations beyond these bounds reflects right- and left-censoring in the patent dataset. Since the majority of variation is concentrated within a ten-year window surrounding acquisition, the identification of pre- and post-trends relies most heavily on this central range.

### A.2 Alternative Control Groups

Using three alternative control groups confirms the robustness of the main citation findings:

1. **All patents in G and H sections**: The post-acquisition effect is 1.17 additional citations per year, similar in magnitude and significance to the baseline.

2. **Patents in untreated CPC groups**: The estimated effect is 2.20 citations per year (specification with CPC-year FE) or 1.71 (patent FE). The larger magnitude reflects that untreated CPC groups have lower average citation rates (0.55 vs. 0.80 in treated groups), making any post-treatment shift appear relatively larger.

3. **Other patents owned by the acquiring firm**: The post-acquisition coefficient is 0.92 (CPC-year FE) or 0.88 (patent FE) citations per year. These smaller magnitudes, relative to the baseline, are expected given the acquirer's high average citation rate (0.98). The acquired patents still exhibit a measurably larger citation boost than the acquirer's own portfolio, indicating that the effect is not driven by firm-wide dynamics.

Across all four control group specifications, the post-acquisition increase in citations to acquired patents is positive, economically meaningful, and statistically significant.
