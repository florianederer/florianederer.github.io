# Killer Acquisitions

**Colleen Cunningham** (London Business School)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Song Ma** (Yale School of Management)

*Journal of Political Economy*, Vol. 129, No. 3, pp. 649–702, March 2021

---

## Abstract

This paper argues incumbent firms may acquire innovative targets solely to discontinue the target's innovation projects and preempt future competition. We call such acquisitions "killer acquisitions." We develop a parsimonious model illustrating this phenomenon. Using pharmaceutical industry data, we show that acquired drug projects are less likely to be developed when they overlap with the acquirer's existing product portfolio, especially when the acquirer's market power is large due to weak competition or distant patent expiration. Conservative estimates indicate 5.3 percent to 7.4 percent of acquisitions in our sample are killer acquisitions. These acquisitions disproportionately occur just below thresholds for antitrust scrutiny.

---

## Theory

### Setup

The model has a three-period timeline. In $t=0$, an entrepreneur $E$ with a single project is born. There are also $n \geq 1$ incumbent firms, each possessing an existing differentiated product. One of these $n$ incumbents, called the potential acquirer $A$, can acquire the entrepreneur at an endogenously determined takeover price $P$. In $t=1$, the project's owner decides whether to develop the project. Let $\rho^{A}$ and $\rho^{E}$ be the probabilities that the project will ultimately be successful if the acquirer or the entrepreneur develops it, $k$ be the cost of developing the project, and $L$ be the project's liquidation value if development does not continue. In $t=2$, uncertainty about the project's success is resolved and all firms engage in Bertrand competition with differentiated products.

### Product Market Competition

The acquirer's profits satisfy the following ranking:

$$\pi^{A}_{acq,S} > \pi^{A}_{acq,F} = \pi^{A}_{\neg acq,F} > \pi^{A}_{\neg acq,S} > 0$$

where subscripts $acq$ and $\neg acq$ denote acquired versus non-acquired, and $S$ and $F$ denote project success and failure respectively. The entrepreneur's profits satisfy $\pi^{E}_{\neg acq,S} > \pi^{E}_{\neg acq,F} = 0$.

The acquirer's profits when the project fails are the same whether or not he acquires it ($\pi^{A}_{acq,F} = \pi^{A}_{\neg acq,F}$) because in both cases he competes against $n-1$ single-product incumbents. When the project succeeds and the acquirer did not acquire it, he faces $n$ competitors including the entrepreneur with a superior new product, yielding the lowest profit $\pi^{A}_{\neg acq,S}$.

### Development Decision

The key to the model is that an acquiring incumbent gains less from successfully developing a new project than an independent entrepreneur. Define the development gains:

$$\Delta^{E} \equiv \pi^{E}_{\neg acq,S} - \pi^{E}_{\neg acq,F} \quad \text{and} \quad \Delta^{A} \equiv \pi^{A}_{acq,S} - \pi^{A}_{acq,F}$$

As long as the acquirer's existing product and the new project are imperfect substitutes, $\Delta^E > \Delta^A$. This is the **replacement effect** (Arrow 1962): the new product cannibalizes some of the profits of the acquirer's existing product, while an entrepreneur has no existing product to cannibalize.

The development decisions are determined by:

$$\rho^{E} \Delta^{E} - k \geq L \quad \text{and} \quad \rho^{A} \Delta^{A} - k \geq L$$

Rewriting yields the development cost thresholds:

$$k^{E} \equiv \rho^{E} \Delta^{E} - L \quad \text{and} \quad k^{A} \equiv \rho^{A} \Delta^{A} - L$$

**Proposition 1 (Overlap):** An incumbent that acquires a project continues development if $k \leq k^{A}$, while an entrepreneur continues if $k \leq k^{E}$. For any product market overlap, $k^{E} > k^{A}$ if and only if $\frac{\Delta^{E}}{\Delta^{A}} > \frac{\rho^{A}}{\rho^{E}}$.

Unless the acquirer benefits from synergies large enough to outweigh the replacement effect, the entrepreneur has stronger incentives to continue development. When $k$ falls in the intermediate range between $k^{A}$ and $k^{E}$, an incumbent acquirer will terminate the project while an independent entrepreneur would have developed it — giving rise to killer acquisitions.

**Proposition 2 (Competition):** For any product market overlap, the difference $k^{E} - k^{A}$ is strictly decreasing in $n$.

As the number of existing competitors $n$ increases, cannibalization losses from a new product are spread over more firms, reducing the replacement effect and making the acquirer's development decisions more similar to the entrepreneur's. Killer acquisitions are therefore less prevalent in more competitive markets.

**Proposition 3 (Patent Life):** For any product market overlap, the difference $k^{E} - k^{A}$ is strictly increasing in the remaining patent life $T^{A}$ of the acquirer's existing product, provided development synergies are not too large.

When the acquirer's overlapping patent has a long remaining life, the replacement effect remains large. As the patent nears expiry, generic competition destroys profits on the existing product, eliminating the cannibalization concern and aligning the acquirer's development incentives with the entrepreneur's.

With generic competition after patent expiry in $T^A$ years, the development decisions become:

$$\rho^{E} \left(\frac{1-\delta^{T^{A}}}{1-\delta} \Delta^{E} + \frac{\delta^{T^{A}}-\delta^{T^{E}}}{1-\delta} \Delta_{gen}\right) - k \geq L$$

$$\rho^{A} \left(\frac{1-\delta^{T^{A}}}{1-\delta} \Delta^{A} + \frac{\delta^{T^{A}}-\delta^{T^{E}}}{1-\delta} \Delta_{gen}\right) - k \geq L$$

where $\Delta_{gen}$ is the common development gain after generic entry, which is identical for both entrepreneur and acquirer since the acquirer no longer faces cannibalization.

### Acquisition Decision

Killer acquisitions (where the acquirer terminates the project) occur in the region $k^{E} \geq k > k^{A}$, provided the **efficiency effect** exceeds the **replacement effect**:

$$\underbrace{\rho^{E} (\pi^{A}_{acq,F}-\pi^{A}_{\neg acq,S})}_{\text{efficiency effect}} \geq \underbrace{\rho^{E} \Delta^{E} - k - L}_{\text{replacement effect}}$$

The efficiency effect captures the gain to the acquirer from preventing the entrepreneur from entering and destroying his existing profits. The replacement effect reflects the higher valuation that must be paid to compensate the entrepreneur for her stronger development incentives.

Acquisitions with continued development (where both parties would develop) occur when:

$$\underbrace{\rho^{E} (\pi^{A}_{acq,F}-\pi^{A}_{\neg acq,S})}_{\text{efficiency effect}} \geq \underbrace{\rho^{E} \Delta^{E} - \rho^{A} \Delta^{A}}_{\text{replacement effect}}$$

**Proposition 4 (Acquisition):** The acquirer may have strictly positive incentives to acquire the entrepreneur if there is product market overlap or if the acquirer's development synergies are sufficiently large. Otherwise, the acquirer never has strictly positive incentives to acquire.

This proposition implies that acquisitions should be more likely when the acquirer's products overlap with the target's project, because the strategic motive (preventing future competition) is otherwise absent. Synergy-based theories predict the same positive correlation between overlap and acquisition likelihood, but they produce the opposite prediction for development: under synergies, acquired overlapping projects should be *more* likely to be developed, not less.

---

## Data

### Drug Development Data

The analysis uses Pharmaprojects from Pharma Intelligence, which tracks drug projects from early-stage development through to launch or discontinuation. The sample covers 16,015 drug projects originated by 4,637 firms, initiated between 1989 and 2010. Over this period, drug project initiations increase from roughly 500 per year in the 1990s to around 1,000 per year in later periods.

Drug development follows a standard sequence: preclinical screening, then Phase I trials (20–100 healthy volunteers, testing safety), Phase II trials (hundreds of patients, testing efficacy, lasting up to two years), and Phase III trials (hundreds to thousands of participants, typically one to four years). Successful completion enables firms to file a New Drug Application (NDA) with the FDA.

More than half of firms in the sample originate only one drug over this period; nearly 70 percent originate two projects or fewer, consistent with the pattern of small innovative firms whose projects are subsequently developed by large incumbents.

**Overlap definition.** A drug project is classified as overlapping with an acquirer's portfolio if the acquirer has an existing project or product in the same **therapeutic class** (disease or condition targeted, e.g., antihypertensive) and the same **mechanism of action** (biological interaction, e.g., calcium channel antagonist). This narrow definition identifies potential substitutes — drugs that, if successfully developed, would directly compete with the acquirer's existing product. In the sample, approximately 23 percent of acquired drug projects overlap with their acquirer by this definition (27 percent overlap in therapeutic class only; 50 percent do not overlap).

### Acquisition Data

Acquisition events are compiled from three sources: Thomson Reuters SDC Platinum (M&A announcements and completions), Thomson Reuters RecapIQ (biotechnology deals from company press releases and SEC filings), and SDC VentureXpert (VC-backed early-stage start-ups). The combined database represents 22 percent of drug projects having an acquisition recorded during development.

---

## Empirical Analysis

### Empirical Design

The main specification uses a project-year panel:

$$Development_{i,t} = \beta \cdot I(Acquired)_i \times I(Post)_{i,t} \times I(Overlap)_i + \gamma_1 \cdot I(Acquired)_i \times I(Post)_{i,t} + \gamma_2 \cdot I(Acquired)_i \times I(Overlap)_i + \gamma_3 \cdot I(Acquired)_i + \alpha_{FE} + \varepsilon_{i,t}$$

where $Development_{i,t}$ is a dummy for whether drug $i$ has a development event in year $t$, $I(Acquired)_i$ indicates acquisition, $I(Post)_{i,t}$ indicates post-acquisition years, and $I(Overlap)_i$ indicates overlap. Standard errors are clustered at the drug project level. The key coefficient $\beta$ on the triple interaction captures the additional change in development probability for overlapping acquisitions relative to non-overlapping acquisitions, post-acquisition.

### Development of Drug Projects Post-Acquisition

The main results are estimated with a variety of fixed effects. Column 1 includes project age and vintage fixed effects. Column 2 refines age fixed effects into age × therapeutic class × MOA fixed effects. Column 3 adds originator firm fixed effects. Column 4 includes project fixed effects (the tightest specification).

**Key result (column 4):** Acquired drug projects that overlap with the acquirer's portfolio are **23.4 percent** less likely to have continued development activity post-acquisition compared to non-overlapping acquired projects. Given the unconditional development probability of 19.9 percent, this is a large and economically significant effect.

Pre-acquisition development trajectories for overlapping and non-overlapping acquired projects are statistically indistinguishable (column 6, with indicators for the three pre-acquisition years), confirming that the result is not driven by pre-existing differences.

Column 5 implements propensity score reweighting (following Guadalupe, Kuzmina, and Thomas 2012) to control for time-varying selection into acquisition. Results remain robust.

A supplementary analysis distinguishes between the same therapeutic class with the same mechanism of action ("tight" overlap) and the same therapeutic class only. Both types predict reduced development, with the tight-overlap effect being larger and more consistently significant.

### Alternative Subsamples and Specifications

Using a collapsed two-period analysis with "no development" as the outcome, overlapping acquired projects are **20.9 percent** more likely to have no post-acquisition development events whatsoever (14.9 percentage points out of a base of 71.1 percent), consistent with immediate and permanent termination rather than delayed development.

For single-project targets — eliminating the concern that acquirers are optimally selecting which projects to continue among multiproject targets — the effect of overlap on post-acquisition development is **larger in magnitude** than in the full sample (–12.1 percentage points), ruling out optimal project selection as an explanation.

Among projects that do have some post-acquisition development, there is no significant difference in development rates between overlapping and non-overlapping acquisitions, confirming that the main result is driven entirely by projects that are terminated rather than those that continue.

### Product Market Competition

Splitting the sample by the median count of existing products in the same therapeutic class × MOA, the effect of overlap is concentrated in **low-competition markets**:

- Low competition: overlapping acquired projects are 6.5 percentage points (41.2 percent relative to the unconditional rate) less likely to be developed
- High competition: coefficient of 0.017, statistically insignificant

The interaction term confirms a statistically significant difference between the two groups. This result supports Proposition 2: as the number of existing competitors increases, the replacement effect shrinks and killer acquisition incentives diminish.

### Heterogeneity across Patent Expiration

Among overlapping acquired projects, the decrease in development is **mitigated when the acquirer's overlapping patent is near expiry** (within five years). Projects for which the relevant acquirer patent is near expiration are more likely to have development events post-acquisition, consistent with Proposition 3: when generic entry is imminent, the replacement effect is small and the killer acquisition motive diminishes.

### Evidence from Clinical Trials

Using projects that start Phase I clinical trials and examining their likelihood of starting Phase II:

$$PhaseII_{i} = \beta \cdot I(Acquired)_i \times I(Overlap)_i + \alpha_{FE} + \varepsilon_{i}$$

Projects acquired by firms with overlapping products are **17.7 percentage points** (46.6 percent) less likely to progress to Phase II, relative to the base rate of 38 percent for acquired projects. This result is concentrated in low-competition markets (–35.6 percentage points in low-competition vs. –14.2 percentage points in high-competition markets, with the difference statistically significant).

### Acquisition Decisions

Using a conditional logit model, the paper constructs pseudo acquirer-target pairs (random matching and size-matched controls) and estimates:

$$Acquirer\text{-}Target_{ijd,t} = \beta \cdot I(Overlap)_{ijd,t} + \alpha_{FE} + \varepsilon_{ijd,t}$$

**Key result:** The estimated marginal effect of 0.626 implies that acquisitions are **almost four times more likely** when the incumbent's products overlap with the target's drug projects, compared to the baseline acquisition rate of 16.7 percent. This pattern holds under both random and size-matched control samples and for both tight (same therapeutic class × MOA) and broad (same therapeutic class only) overlap definitions, with the effect being larger in low-competition markets.

### Antitrust Review Thresholds

In the pharmaceutical industry, acquisitions below certain transaction value thresholds are exempt from mandatory premerger notification to the FTC under the Hart-Scott-Rodino (HSR) Antitrust Improvements Act. Deals below roughly $200 million (adjusted annually) typically escape regulatory scrutiny.

Plotting the distribution of acquisition sizes in a $\pm$5 percent window around the HSR review threshold reveals **clear bunching just below the threshold for overlapping acquisitions but not for non-overlapping acquisitions**. Among acquisitions near the threshold:

| Outcome | 5% Below Threshold | 5% Above Threshold | Difference |
|---|---|---|---|
| Launched | 1.8% | 9.1% | –7.3%** |
| Discontinued | 94.6% | 83.3% | +11.3%** |
| Active | 3.6% | 7.6% | –4.0% (not sig.) |

A pseudo threshold (base value of $150 million in 2000) shows no significant differences above or below, confirming that the pattern at the real threshold reflects strategic behavior rather than a general size-development relationship.

---

## Discussion

### Alternative Explanations

Any alternative explanation must account not only for why acquired projects are more likely to be terminated, but specifically why **overlapping** acquired projects are terminated at higher rates than non-overlapping acquired ones.

**Informational asymmetries.** Asymmetric information should be *lower* for overlapping acquisitions, since the acquirer has direct knowledge of the relevant science and market. The observed patterns are therefore unlikely to reflect a "market for lemons" story.

**Optimal project selection.** If acquirers develop only the most promising projects among multiproject targets, the effect should be weaker for single-project acquisitions. It is instead *larger*, ruling out optimal project selection.

**Technology redeployment.** Using the Tanimoto chemical similarity measure, drugs initiated by acquirers after acquisition of an overlapping drug are no more chemically similar to the acquired drug than pre-acquisition projects (coefficient 0.001, economically negligible relative to the sample mean of 0.133). Patent citation analysis yields the same null result. No evidence supports technology redeployment.

**Human capital redeployment.** Using the Harvard Business School Patent Dataverse to track inventor mobility:
- Only 22 percent of pre-acquisition inventors move to the acquiring firm; 78 percent move elsewhere
- Retained inventors' patenting drops by 30 percent (from 4.57 to 3.16 patents per five years)
- Inventors who leave experience a smaller productivity drop (<10 percent)

These patterns are inconsistent with efficient human capital redeployment driving the results.

**Salvage acquisitions.** If firms acquire already-failing targets for their residual assets, development rates should decline pre-acquisition and acquisition values should be lower for overlapping targets. Neither is observed: pre-acquisition development rates are statistically indistinguishable between overlapping and non-overlapping acquired projects (column 6 of the main table), and overlapping acquisitions do not have significantly lower values (coefficient on Overlap in log acquisition value regressions is 0.025–0.126, statistically insignificant).

### Frequency and Importance of Killer Acquisitions

The back-of-the-envelope calculation uses the following framework. The unconditional development probability is 19.9 percent. Acquired projects with overlap (22.7 percent of acquired projects) continue at an adjusted rate of 13.4 percent. Assuming two types: pure killer acquisitions (0 percent development probability) and others (17.5 percent development probability, same as non-overlapping acquisitions), solving $13.4\% = \nu \times 0 + (1-\nu) \times 17.5\%$ gives $\nu = 23.4\%$.

Therefore:
- **5.3 percent** of all acquisitions ($= 23.4\% \times 22.7\%$) are killer acquisitions, approximately **46 per year**
- Using the non-acquired development rate (19.9 percent) as the counterfactual instead: **7.4 percent** of acquisitions are killer acquisitions, approximately **63 per year**
- Using the never-developed threshold: a minimum of 29 killer acquisitions per year

These estimates are conservative lower bounds, since they assume killer acquisitions lead to immediate termination with zero probability of development and that there are no synergies that would partly mask the killing effect.

Eliminating killer acquisitions would raise the pharmaceutical industry's aggregate drug project development rate by approximately **4.3 percent**, or about 13 additional drug projects developed per year (out of an annual average of 1,630 projects). For context, the Orphan Drug Act — a major innovation policy intervention — generated roughly 25 more clinical trials per year from 1981 to 1994. Eliminating killer acquisitions would achieve effects at least half that size.

During approximately the same period, the FTC recorded 10–20 pay-for-delay patent settlements per year. Killer acquisitions (46–63 per year) occur at substantially higher frequency than pay-for-delay settlements and likely cause at least comparable anticompetitive harm.

### Welfare Analysis

Killer acquisitions have an unambiguously negative effect on consumer surplus when they leave ex-ante innovation incentives unaffected: consumers face fewer drugs and those that are developed are sold at higher prices. However, the overall welfare effect is ambiguous because the prospect of acquisition may incentivize entrepreneurial idea generation. If the entrepreneur captures some of the surplus from the acquisition, the existence of the acquisition channel may increase ex-ante innovation. Whether this positive incentive effect outweighs the ex-post efficiency loss depends on the elasticity of the entrepreneur's innovation response.

Killer acquisitions are less likely to occur when incumbents face significant existing competition. This creates a **positive reinforcement loop**: more competition today reduces killer acquisition incentives, which leads to more future competition, which further reduces killer acquisition motives.

---

## Conclusion

This paper documents that incumbent firms acquire innovative targets and terminate their innovative projects to preempt future competition. Using comprehensive pharmaceutical industry data, acquired drug projects are 23.4 percent less likely to be developed when they overlap with the acquirer's existing portfolio. This effect is concentrated in low-competition markets and when the acquirer's overlapping patent is far from expiry. Overlapping acquisitions are also almost four times more likely to occur than non-overlapping acquisitions, and they bunch just below the HSR antitrust review threshold. Alternative explanations — optimal project selection, technology redeployment, human capital redeployment, and salvage acquisitions — do not account for the results.

Conservative estimates suggest 5.3 to 7.4 percent of pharmaceutical acquisitions are killer acquisitions, totaling 46 to 63 per year. The phenomenon is not specific to pharmaceuticals: acquisitions have become the dominant exit mode for VC-backed startups across industries, particularly in the tech sector, suggesting that killer acquisitions may be widespread. The large number of acquisitions of small entrepreneurial start-ups by large incumbents in technology would make a fruitful case for investigating whether killer acquisitions extend beyond pharmaceuticals.

Antitrust policy should closely scrutinize acquisitions that plausibly prevent the development of future competing products, particularly because killer acquisitions routinely avoid mandatory regulatory review by occurring below the HSR transaction value threshold. The magnitude of the Schumpeterian gale of creative destruction may be smaller than previously documented: rising acquisition activity by powerful incumbents may be inhibiting technological progress by acquiring and terminating nascent innovation.
