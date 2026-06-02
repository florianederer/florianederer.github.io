# Disclosure and the Pace of Drug Development

**Colleen Cunningham** (University of Utah)
**Florian Ederer** (Boston University Questrom School of Business, CEPR, ECGI, and NBER)
**Charles Hodgson** (Yale University)
**Zhichun Wang** (Yale University)

*Working Paper*

---

## Abstract

Policies that mandate disclosure of innovative project outcomes aim to increase innovation by limiting wasteful duplicative innovation. Yet, such policies change not only the ex-post information environment but also firms' ex-ante innovation incentives. Firms may slow down their own innovation efforts in anticipation of increased disclosure by others. Using the 2017 FDA Final Rule, which mandated timely disclosure of clinical trial results, we document a substantial increase in results disclosure — including previously underreported failed trials — accompanied by a significant slowdown in the pace of drug development. Phase 2 trial completion times increased by over 200 days, Phase 1-to-Phase 2 transition rates fell from roughly 70% to below 50% within a year, and active trial sites in oncology Phase 2 trials declined by more than 50% after two years. These responses are concentrated in drugs with more technologically related trials pending disclosure, consistent with strategic free-riding on anticipated information. We develop a dynamic model of trial investment and show that the key mechanism — increased disclosure crowds out private information acquisition — is both theoretically grounded and structurally identified from the data.

---

## Theoretical Framework

### Setup

The paper develops a two-period, two-firm model to fix ideas about the incentives driving trial delay. In period 1 each firm chooses whether to initiate a trial, $a_{f1} \in \{0,1\}$, at cost $c$. Conditional on running a trial, the firm observes a binary signal $s_f \in \{0,1\}$ with $\Pr(s_f = 1) = p$. Signals across firms are correlated with probability $\rho$ — the informativeness parameter capturing the extent to which outcomes of related trials provide useful information. If a firm waits until period 2, it may observe the period-1 outcome of the other firm (with probability $\alpha$, the disclosure parameter). A firm's period-2 payoff from a successful drug is reduced by a competition parameter $\lambda \in [0,1]$ that captures the degree of business-stealing.

The theoretical framework provides a mapping from model parameters to empirical objects. The disclosure parameter $\alpha$ corresponds to the change induced by the Final Rule. The informativeness parameter $\rho$ captures cross-drug learning within a mechanism of action. The competition parameter $\lambda$ captures interactions within the same therapeutic class.

### Key Results

**Proposition 1 (Delay under Learning):** If $\lambda = 1$ (no competition), there exists a threshold $\rho^*$ such that for $\rho > \rho^*$, delay equilibria exist — firms prefer to wait and free-ride on information from other firms' trials.

**Proposition 2 (Disclosure Causes Delay):** If $\lambda = 1$, then $\frac{\partial \gamma}{\partial \alpha} < 0$: a higher disclosure probability $\alpha$ increases the incentive to delay, since firms value the option of observing others' outcomes more.

**Proposition 3 (Delay under Competition):** If $\rho = 0$ (no technological learning), there exists a threshold $\lambda^*$ such that for $\lambda < \lambda^*$, delay equilibria exist due to preemption incentives — firms want to see whether a competing drug succeeds before committing to costly development.

**Proposition 4 (Disclosure Causes Delay under Competition):** If $\rho = 0$, then $\frac{\partial \gamma_1}{\partial \alpha} < 0$: mandatory disclosure also increases delay in competitive environments.

**Proposition 5 (Welfare):** Full disclosure ($\alpha = 1$) need not be socially optimal. The socially optimal disclosure policy $\alpha^{SP} < 1$ is possible because the social planner internalizes that disclosure reduces private incentives to experiment.

---

## Industry and Institutional Background

### Drug Development Background

Drug development proceeds through a sequence of clinical trial phases. Following preclinical evaluations, firms submit an Investigational New Drug (IND) application to the FDA and proceed through:

- **Phase 1:** First human administration, typically 20–100 volunteers, lasting several months. Primary goal is safety and dosage. About 70% of drugs pass.
- **Phase 2:** Several hundred patients, up to two years. Focuses on efficacy while monitoring safety. About one-quarter to one-third advance.
- **Phase 3:** 300–3,000 participants, one to four years. Confirms effectiveness and compares to existing treatments. About half to two-thirds of drugs that enter are eventually launched.

Overall, about 10% of drugs entering clinical trials reach the market. Drug development is costly; estimates for the total cost of bringing a new drug to market range from just over $100 million to more than $1 billion.

### Policy Background: The FDA Final Rule

FDA policies on clinical trial disclosure evolved over two decades:

- **1997:** FDA Modernization Act required registration of selected trials under IND for serious or life-threatening conditions.
- **2000:** ClinicalTrials.gov made publicly available.
- **2005:** The International Committee of Medical Journal Editors (ICMJE) required trial registration as a condition of journal publication, causing a 73% jump in registrations.
- **2007:** FDA Amendments Act (FDAAA) required Phase 2+ trial registration and summary results submission, with fines of $10,000/day for noncompliance. However, enforcement was lax and result posting remained spotty — only 39.5% of trials reported results within a year.

Importantly, the 2007 FDAAA did not require results disclosure for drugs that were not subsequently approved. The FDA added the **Final Rule** (FR) amendment to the FDAAA, announced in 2014 and enacted in 2017. Key features of the Final Rule:

1. All applicable clinical trials must post results **regardless of FDA approval status** for trials with primary completion dates on or after January 18, 2017.
2. Results must specify outcome metric, time points of assessment, and clarity on what is measured.
3. Mandatory inclusion of baseline characteristics (race, ethnicity, primary outcome-relevant measures).
4. Strengthened adverse event reporting: previously optional fields made mandatory, deaths require detailed documentation.
5. Submission of full protocols and statistical analysis plans (SAPs) required.

---

## Data

The analysis uses two data sources from Informa:

**Pharmaprojects** tracks pharmaceutical development projects at the drug level using data from pharmaceutical companies and researchers, press releases, patent filings, conference proceedings, regulatory filings, and the medical literature. The dataset has been used extensively in prior research on drug development, including Cunningham, Ederer, and Ma (2021).

**Trialtrove** provides detailed data on individual clinical trials: phase, start date, completion date, results disclosure date, and outcomes. Trials are classified as successful (positive results only) or unsuccessful (negative, inconclusive, or early termination). The two datasets are merged using a crosswalk file from Informa.

The main analytical sample includes all industry-sponsored pharmaceutical trials with activity between 2010 and 2019. Table 1 summarizes trial length and reporting statistics:

- Mean Phase 1 trial length: 549 days (~18 months); Phase 2: 914 days; Phase 3: 944 days.
- Reporting rates: Phase 1 ~21% (excluded from FDA requirements); Phase 2 ~71%; Phase 3 ~80%.
- Mean reporting delay: Phase 1 ~487 days; Phase 2 ~432 days; Phase 3 ~364 days.
- Approved drugs average 2.56 Phase 1, 1.97 Phase 2, and 3.08 Phase 3 trials before approval.

The paper also uses within-trial data from ClinicalTrials.gov, measuring the number of **active sites** (hospital or clinic locations recruiting patients) over the course of each trial, constructed from the change log of each trial's ClinicalTrials.gov entry. The main site-count sample includes all industry-sponsored Phase 2 trials between 2010 and 2019. Oncology Phase 2 trials are the focus of within-trial investment analysis.

---

## Empirical Analysis

### Disclosure of Trial Results

Comparing Kaplan-Meier failure curves for pre-policy (2010–2016) and post-policy (2017–2019) completed Phase 2 industry trials:

- Two-year disclosure probability rose from **68%** (2010–2016) to **78%** (2017–2019).
- For non-industry trials, the two-year disclosure probability rose from ~20% to ~60%.
- A large mass of post-2017 trials were reported at or immediately after the one-year reporting deadline, confirming that the policy and associated penalties drove the shift.
- The increase in aggregate reporting was primarily driven by **unsuccessful trials**: the two-year reporting rate for unsuccessful trials rose from 60% to 75%; for successful trials, from 85% to 92%.

### Time to Complete and Time to Start Trials

**Trial completion (Phase 2):**
- Median completion time rose from ~700 days (pre-policy) to ~900 days (post-policy), an increase of more than 200 days.
- One- to two-year completion probability fell from 20–25% (pre-policy) to 15% (post-policy), with the decline beginning in 2015–2016 after the Final Rule was announced but before it took effect.
- Non-industry trial completion rates did not slow, despite increased disclosure compliance — consistent with strategic rather than mechanical responses.

**Phase 1-to-Phase 2 transition:**
- One-year follow-up probability (a new trial started within a year of Phase 1 completion) fell from ~70% (pre-policy) to below 50% (post-policy).

These patterns cannot be explained by strategic manipulation of reported completion dates: the Phase 2-to-Phase 3 transition interval did not shorten following the policy change, indicating that the observed delays reflect genuine slowdowns in development pace.

### Within-Trial Investment (Active Sites)

Using oncology Phase 2 trials matched to ClinicalTrials.gov site data:

- For trials active two years post-start, pre-policy trials averaged ~8 active sites; post-policy trials averaged fewer than 4 — a **reduction of over 50%**.
- Year fixed effects from a regression of active sites on year and months-since-start show a significant drop after 2017: approximately one fewer site per trial on average in the post-policy period.

### Heterogeneous Responses by Disclosure Environment

The paper tests whether the slowdown in investment is more pronounced for drugs with more technologically related trials pending disclosure. For each drug $j$, $M_j$ is the set of drugs sharing a mechanism of action (MOA). $Unrep_{tj}$ is the log count of drugs in $M_j$ with completed but unreported Phase 2 trials at date $t$.

Regressions of trial completion probability and active site counts on $Post_{tj}$, $Unrep_{tj}$, and their interaction show:

- The interaction between $Unrep_{tj}$ and $Post_{tj \geq 2017}$ is **negative and statistically significant** for both trial completions (coefficient $-0.0136$, significant at 1%) and active sites (coefficient $-1.2464$, significant at 5%).
- Including the interaction absorbs most of the direct $Post_{tj}$ effect, indicating that much of the post-policy investment slowdown is attributable to increased sensitivity to the disclosure environment.
- Drugs in **small markets** also show an additional post-policy slowdown (coefficients $-0.0042$ to $-0.0046$ for trial completion), consistent with competitive preemption effects.

Results are robust to truncating at March 2020, ruling out COVID-19 as a confound.

---

## Learning from Trial Results

### Cross-Drug Learning

Using monthly drug-level regressions following Krieger, Prousa, and Pelkmans (2021), the paper estimates how the cumulative count of disclosed successful and unsuccessful Phase 2 trials — from the same drug, same therapeutic class ($T_j$), and same mechanism of action ($M_j$) — predicts new trial starts:

$$Start_{jt} = \beta_1^{Same} Suc_{jt} + \beta_2^{Same} UnSuc_{jt} + \beta_1^{TC} \sum_{k \in T_j} Suc_{kt} + \beta_2^{TC} \sum_{k \in T_j} UnSuc_{kt} + \beta_1^{MOA} \sum_{k \in M_j} Suc_{kt} + \beta_2^{MOA} \sum_{k \in M_j} UnSuc_{kt} + \alpha_j + \gamma_t + \epsilon_{jt}$$

**Key findings (Phase 2 starts as dependent variable):**

*Same drug:*
- Successful Phase 2: +1.04pp (not significant)
- Unsuccessful Phase 2: −1.67pp (significant at 1%)

*Same mechanism of action ($M_j$ — technological learning):*
- Successful Phase 2 on related drug: **+1.65pp** (significant at 1%)
- Unsuccessful Phase 2 on related drug: **−1.17pp** (significant at 1%)

*Same therapeutic class ($T_j$ — competitive learning):*
- Successful Phase 2 on competing drug: **−1.08pp** (significant at 10%)
- Unsuccessful Phase 2 on competing drug: **+1.86pp** (significant at 5%)

The opposing signs for same-MOA versus same-therapeutic-class effects are consistent with:
- **Technological learning:** success of a same-mechanism drug signals the mechanism works, encouraging investment in drug $j$.
- **Competitive preemption:** success of a competing drug raises the probability of a viable market rival, discouraging further development of drug $j$.

Learning effects are most pronounced for Phase 2 outcomes. Phase 3 outcomes for same-therapeutic-class drugs tend to carry the opposite sign, reflecting dominant competitive preemption when a competitor clears the final approval hurdle.

---

## Dynamic Model of Trial Investment

### Setup

The structural model introduces a dynamic learning environment where firm $j$ develops drug $j$ within MOA group $m$. Drug effectiveness is:
$$\lambda_j = \mu_m + \lambda_j^o$$
where $\mu_m \sim \mathcal{N}(\mu_M, \sigma_M)$ is the group-level productivity component (common to all drugs in $m$) and $\lambda_j^o \sim \mathcal{N}(0, \sigma_\lambda)$ is the drug-specific component. Observing outcomes of other drugs in $M_j$ is informative about $\mu_m$ and hence about $\lambda_j$.

The firm's state $S_j = \{\tilde{\mu}_m, \tilde{\sigma}_m, \tilde{\lambda}_j^o, \tilde{\sigma}_j; A, O, C\}$ includes beliefs about group-level and idiosyncratic productivity, the number of active trial sites $A$, the number of ongoing related trials $O$, and completed-but-unreported related trials $C$.

Each period, the firm receives an own signal:
$$s_{jt} \sim \mathcal{N}\!\left(\lambda_j, \frac{\sigma_o}{A}\right)$$
More active sites reduce signal variance and generate faster learning. Completed-but-unreported trials $k \in C$ disclose with probability $\alpha_D$; upon disclosure, the firm observes the average signal from trial $k$:
$$S_k \sim \mathcal{N}\!\left(\mu_m + \lambda_k^o, \frac{\sigma_o}{\bar{A}}\right)$$

### Value Function

The firm's value function captures three choices:
$$V(S) = \max\!\left\{\beta E[V(S')] - cA,\; \max_{A^* \in [0,\bar{A}]}\!\left\{\beta E[V(S')|A^*] - cA - \delta\right\},\; \pi(S)\right\}$$
where $c$ is the per-site cost, $\delta$ is the adjustment cost of changing $A$, and the terminal payoff is:
$$\pi(S) = \max\{\tilde{\mu}_m + \tilde{\lambda}_j^o, 0\}$$

The value function is solved by value function iteration with the value function approximated by a neural network (following Bertsekas; applied to a similar setting by Hodgson and Lewis).

### Key Implications

The model shows that as $C$ (completed-but-unreported related trials) increases, the optimal number of active sites $A^*$ declines monotonically — firms prefer to wait for external information rather than generating costly private signals. This decline is **steeper when $\alpha_D$ is higher**, implying that mandatory disclosure policies amplify the crowd-out of private investment. These predictions are consistent with the empirical findings.

---

## Estimation

The model is estimated by simulated method of moments (SMM) / indirect inference. The disclosure rates $\alpha_{D1}$ and $\alpha_{D2}$ for the pre- and post-policy periods are estimated directly from data. The remaining structural parameters are:

$$\theta = (\mu_M, \sigma_M, \sigma_\lambda, c, \delta, \sigma_o)$$

**Moments (10 total):**
1–2. Average active sites in each era (identifies $c$).
3–4. Average trial length in each era (identifies $\sigma_M + \sigma_\lambda$).
5. Average maximum sites per trial (identifies $\mu_M$).
6. Average minimum sites per trial (identifies $\mu_M$).
7. Average number of site changes (identifies $\delta$).
8. Interaction coefficient from active-sites regression (identifies $\sigma_M$, $\sigma_\lambda$).
9. Interaction coefficient from trial-completion regression (identifies $\sigma_M$, $\sigma_\lambda$).
10. Slope from regression of trial completion on active sites (identifies $\sigma_o$).

The estimator minimizes:
$$\theta^* = \arg\min_\theta \left(g(\theta) - \hat{g}\right)' W \left(g(\theta) - \hat{g}\right)$$
where $W = \mathrm{Cov}(\hat{g}_m)^{-1}$ is the optimal weighting matrix.

**Monte Carlo validation:** With true parameters $(\mu_M=-2, \sigma_M=7, \sigma_\lambda=5, c=0.05, \delta=0.3, \sigma_o=60)$, the estimator achieves near-nominal 95% coverage rates ($M=100$: 93–96%; $M=1000$: 91–98%) and low bias across all parameters.

---

## Conclusion

Using pharmaceutical clinical trial data from 2010–2019, the paper documents three main findings. First, the 2017 FDA Final Rule substantially increased the timeliness of results disclosure, particularly for previously underreported failed trials. Second, this policy change was followed by a significant slowdown in the pace of drug development: Phase 2 trials took over 200 days longer to complete, Phase 1-to-Phase 2 transition rates fell by more than 20 percentage points, and active trial sites in oncology Phase 2 trials declined by over 50%. Third, these slowdowns are concentrated in drugs with more technologically related trials pending disclosure, consistent with firms free-riding on anticipated information from competitors.

The results suggest that mandatory disclosure policies involve a fundamental trade-off: while increased transparency reduces duplicative innovation and improves informational efficiency, it may also dampen private incentives to experiment, slowing the pace of drug development overall. The dynamic structural model identifies the crowding-out of private information acquisition as the key mechanism, and the simulated method of moments estimation confirms that the identified parameters can recover the empirical patterns quantitatively.
