# Common Ownership, Competition, and Top Management Incentives

**Miguel Antón** (IESE Business School)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Mireia Giné** (IESE Business School, ECGI, and WRDS)
**Martin Schmalz** (University of Oxford Saïd Business School, CEPR, ECGI, CESIfo, and C-SEB)

*Journal of Political Economy*, Vol. 131, No. 5, pp. 1294–1355, May 2023

---

## Abstract

We present a mechanism based on managerial incentives through which common ownership affects product market outcomes. Firm-level variation in common ownership causes variation in managerial incentives and productivity across firms, which leads to intra-industry and intra-firm cross-market variation in prices, output, markups, and market shares that is consistent with empirical evidence. The organizational structure of multiproduct firms and the passivity of common owners determine whether higher prices under common ownership result from higher costs or from higher markups. Using panel regressions and a difference-in-differences design we document that managerial incentives are less performance-sensitive in firms with more common ownership.

---

## Introduction

The common ownership hypothesis suggests that when large investors own shares in more than one firm within the same industry, those firms may have reduced incentives to compete. Firms can soften competition by producing fewer units, raising prices, reducing investment, innovating less, or limiting entry into new markets. However, top managers rather than investors control firms, firms have hierarchical structures in which operational decisions are delegated to middle managers, and managers may not know the extent of their main investors' shareholdings in other firms. This has fueled a vigorous debate about whether existing evidence on common ownership has a plausible causal interpretation.

In this paper we show that managerial incentives can serve as a mechanism that connects common ownership to softer competition. Our mechanism requires neither communication or coordination between shareholders, managers, or firms nor market-level interventions by shareholders or even top managers. The predictions help organize a large set of existing empirical evidence on how prices, quantities, costs, markups, concentration, and governance choices depend on common ownership.

We embed a canonical managerial incentive design problem with moral hazard in a conventional model of strategic product market competition with potentially diversified owners. The central driving force is that performance-sensitive managerial compensation encourages productivity-improving managerial effort, which in turn has two effects. First, in a setting where product prices are fixed, productivity-improving managerial effort increases firm profitability and is desirable for all types of owners. Second, with endogenous product prices, productivity enhancements also cause firms to set lower prices, which reduces the profitability of competing firms and goes against the interests of common owners. Common owners are therefore more willing to tolerate managerial slack and productive inefficiency at their portfolio firms, predicting a negative relationship between common ownership and the sensitivity of top management incentives to firm performance.

The model also generates predictions on how firms set product prices across different markets. Within the same industry, more commonly-owned firms have optimally weaker managerial incentives that lead to higher costs, and thus higher prices than less commonly-owned "maverick" firms. Even though top managers can only exert a single firm-wide productivity-improving effort, commonly-owned firms compete less aggressively in markets in which they face other commonly-owned firms than in markets in which they face maverick firms.

Our mechanism does not rely on (i) owners having access to sophisticated market-level incentives or communications, (ii) top managers knowing the ownership structure of their own firms or competitors, (iii) top managers making detailed market-specific strategic choices, or (iv) explicit or tacit collusion. Instead, it relies only on unilateral changes in the firm's objective, on top managers who exert firm-wide productivity-improving effort solely based on their own explicit incentives, and on the delegation of product market choices to middle managers who maximize profits based on market demand and firm cost structures alone.

In panel regressions, an interquartile range shift of firm-level common ownership is associated with a 10.5% reduction in CEO wealth-performance sensitivity. This result is robust to alternative measures of managerial incentives, common ownership, and industry definitions. We address identification concerns with a difference-in-differences design based on competitor additions to the S&P 500 index: treated index-incumbent firms experience a 16.4% reduction in CEO wealth-performance sensitivity following the index inclusion of a direct industry competitor.

---

## Theoretical Framework

### Product Market Competition

Consider a single industry with $n$ multiproduct firms. There are $m$ separate product categories (or geographically separate markets) and within each product category there are $n$ differentiated products, one for each firm. The model has two stages. Stage 1 is a standard principal-agent setup in which each firm's majority owner proposes a public incentive contract to the firm's top manager. In Stage 2, each firm's top manager can improve firm productivity (i.e., marginal cost) through costly private effort, and pricing specialists set product market prices to maximize firm profits.

Demand is derived from a representative consumer with quadratic utility, yielding linear demand for each product $i$ in market $l$:

$$q_{i,l}(\vec{p}_l) = A - bp_{i,l} + a \sum_{j \neq i} p_{j,l}$$

where $A$, $b > 0$, $a > 0$, and $b > (n-1)a > 0$, so a firm's own price has a greater impact on its demand than rivals' prices.

Each firm $i$ has a marginal cost given by:

$$c_i = \bar{c} - e_i$$

where $\bar{c}$ is a constant and $e_i$ is the effort exerted by firm $i$'s manager. The profits of firm $i$ are:

$$\pi_i = \sum_{l=1}^{m} \left\{ [p_{i,l} - (\bar{c} - e_i)](A - bp_{i,l} + a \sum_{j \neq i} p_{j,l}) \right\} + \varepsilon_i$$

where $\varepsilon_i$ is a normally distributed profit shock with zero mean and variance $\sigma^2$.

### Top Managers

The manager of firm $i$ is offered a linear compensation contract:

$$w_i = s_i + \alpha_i \pi_i$$

where $s_i$ is a fixed salary and $\alpha_i$ is the incentive slope on firm $i$'s profits. Given normally distributed profit shocks, maximizing the manager's utility is equivalent to maximizing the certainty equivalent:

$$\max_{e_i} CE_i = s_i + \alpha_i \mathrm{E}[\pi_i] - \frac{r}{2}\alpha_i^2 \sigma^2 - \frac{\chi}{2} e_i^2 q_i$$

where $r$ is the degree of risk aversion and $\frac{\chi}{2} e_i^2 q_i$ is the disutility of effort. The compensation contract does not condition on competitor profits $\pi_j$ — this is the optimal linear contract even when owners can contract on rival profits.

### Pricing Specialists

Each firm $i$ has $m$ middle managers ("pricing specialists") who in Stage 2 set prices to maximize firm profit in their product category:

$$\max_{p_{i,l}} \pi_{i,l} = [p_{i,l} - (\bar{c} - e_i)](A - bp_{i,l} + a \sum_{j \neq i} p_{j,l})$$

Pricing specialists maximize individual firm profit without taking common ownership motives into account. Top managers also make no market-specific strategic choices.

### Owners

Each owner $i$ owns a majority stake in firm $i$ as well as shares in other firms $j \neq i$. Owner $i$'s objective function is:

$$\phi_i = \pi_i - w_i + \sum_{j \neq i} \kappa_{ij} (\pi_j - w_j)$$

where $0 \leq \kappa_{ij} \leq 1$ is the value to owner $i$ of a dollar of net profits in firm $j$ relative to a dollar in firm $i$. The profit weight is:

$$\kappa_{ij} = \frac{\sum_o \gamma_{io} \beta_{jo}}{\sum_o \gamma_{io} \beta_{io}}$$

where $\beta_{io}$ is the ownership share of firm $i$ held by shareholder $o$ and $\gamma_{io}$ is shareholder $o$'s control share of firm $i$. Under proportional control, $\gamma_{io} = \beta_{io}$.

In Stage 1, each majority owner maximizes her objective function $\phi_i$ by choosing the incentive contract $(s_i, \alpha_i)$, subject to the manager's individual rationality and incentive compatibility constraints and the Nash equilibrium conditions for Stage 2 actions.

---

## Theoretical Analysis

### Symmetric Owners

For symmetric common ownership ($\kappa_{ij} = \kappa$ for all $i \neq j$), the Stage 2 best-response functions are:

$$e_i = \frac{\alpha_i}{\chi}$$

$$p_{i,l} = \frac{A + b(\bar{c} - e_i) + a \sum_{j \neq i} p_{j,l}}{2b}$$

Stronger incentives lead to greater cost-cutting effort and lower prices. The derivative of the owner's objective with respect to $\alpha_i$ includes a term $\kappa \sum_{j \neq i} \frac{\partial \pi_j^*}{\partial \alpha_i}$, which is negative since stronger incentives for firm $i$'s manager hurt the profits of all other firms $j \neq i$. This establishes the central result:

**Proposition 1.** *The symmetric equilibrium incentives $\alpha_i = \alpha^*(\kappa) < 1$ given to managers decrease and the firms' marginal costs $c_i$ increase with common ownership $\kappa$.*

Common owners are more willing to tolerate managerial slack and productive inefficiency because doing so also leads to less intense competition for the other firms they hold. The higher prices under common ownership are the result of "productive inefficiency" — higher marginal cost $c_i$ caused by reduced managerial incentives and underinvestment in productivity improvements — not higher markups. This is consistent with the empirical finding in Aslan (2019) that in the consumer goods industry, the positive relationship between common ownership and prices is channeled largely through marginal cost variation while markups are unaffected.

**Corollary 1.** *Firm net profits $\pi_i - w_i$ increase with common ownership $\kappa$.*

### Asymmetric Owners: Maverick and Commonly-Owned Firms

Consider an industry with three markets ($\RN{1}$, $\RN{2}$, $\RN{3}$) and three firms. Firm 1 (the "maverick") is owned 100% by an undiversified investor. Firms 2 and 3 each have a majority owner holding share $\delta$ of their primary firm and $(1-\delta)$ of the other commonly-owned firm, so that $\kappa_{23} = \kappa_{32} = (1-\delta)/\delta \equiv \kappa$. The maverick firm competes against each commonly-owned firm in markets I and II; the two commonly-owned firms face each other in market III.

**Proposition 2.** *The equilibrium incentives $\alpha_2^* = \alpha_3^*$ given to managers of the commonly-owned firms 2 and 3 are strictly lower than those given to the manager of the maverick firm 1, $\alpha_1^*$. Therefore $c_2 = c_3 > c_1$. The difference in incentive slopes and costs increases with common ownership $\kappa$.*

**Corollary 2.** *The equilibrium price $p_H^*$ set by the two commonly-owned firms in market III (the "common ownership market") exceeds the price $p_M^*$ they set in the maverick markets, which in turn exceeds the price $p_L^*$ set by the maverick firm. The price difference increases with $\kappa$.*

This price ordering — $p_H^* > p_M^* > p_L^*$ — arises entirely from firm-level variation in managerial incentives, without any market-specific instructions to pricing specialists or any communication about ownership. It provides an explanation for the intra-industry market-level correlations between common ownership and prices documented in the airline, banking, pharmaceutical seed, and consumer goods industries.

**Corollary 3.** *Total equilibrium output $Q_l$ and product market concentration $HHI_l$ are lower in the common ownership market than in the maverick markets. The difference increases with $\kappa$.*

A real-world illustration: prior to its merger with Alaska Airlines in 2017, Virgin America had a radically different ownership structure from other major U.S. airlines. Virgin America was predominantly owned by entrepreneur Richard Branson (30.77%) and activist private equity firm Cyrus Capital Partners (23.52%), neither of whom held large stakes in competitors. In contrast, almost all other U.S. airlines had the same overlapping institutional investors as their largest shareholders. Virgin America won nine straight "Top Domestic Airline" awards from *Travel+Leisure* for its high quality and aggressive pricing, and was described as "the epitome of a market disruptor."

### Model Variations

**Direct control (Proposition 3).** If owners directly control prices or can optimally design incentives for pricing specialists, the equilibrium managerial incentives equal the direct-control incentives:

$$\alpha_i^{DC} = \frac{1}{1 + \frac{\chi r \sigma^2}{q_i}}$$

Managerial incentives still decrease with common ownership, but now through the indirect effect of ownership on firm size rather than through incentive distortion. Prices and price-cost markups increase with common ownership.

**Centralization (Proposition 4).** If all pricing decisions are centralized with the top manager, equilibrium managerial incentives $\alpha_i^*$ still decrease with common ownership while prices increase. Price-cost markups increase with common ownership when $r\sigma^2$ is sufficiently small.

These model variants generate large markup effects of common ownership that are inconsistent with existing empirical evidence (Aslan 2019; Koch and Yoon 2020; Backus, Conlon, and Sinkinson 2021). The baseline model — with delegated pricing to middle managers who care only about their own firm's profit — is consistent with the empirical finding that common ownership primarily affects prices through marginal costs rather than markups.

**Shareholder passivity (Proposition 5).** If designing a managerial incentive contract requires paying a governance cost $g > 0$, for any default incentive slope $\underline{\alpha} < \alpha^{SB}$ there exists a threshold $\underline{\kappa}$ such that:
- If $\kappa < \underline{\kappa}$, the majority owner pays the governance cost and designs executive compensation, resulting in the equilibrium incentives from Propositions 1 and 2.
- If $\kappa \geq \underline{\kappa}$, she does not pay the governance cost, resulting in lower managerial incentives, lower effort, higher costs, and higher prices.

Common owners endogenously choose to be passive. This explains why the five largest common owners (BlackRock, Vanguard, State Street, Fidelity, and T. Rowe Price) are categorized as belonging to the "traditional governance party" that is distinctly deferential to management on compensation proposals. Weak governance and weak competition are jointly optimal for common owners, calling into question policy prescriptions that aim to reduce common owners' governance efforts.

---

## Summary of Theoretical Predictions

| Theory | Prediction | Level | Empirical Evidence |
|--------|-----------|-------|-------------------|
| Props. 1 & 2 | Incentives (−) | Firm | This paper |
| | Costs (+) | Firm | Aslan (2019) |
| | Markups (±) | Firm & Market | Aslan (2019); Koch and Yoon (2020); Backus et al. (2021) |
| Corollary 1 | Profits (+) | Firm | Boller and Scott Morton (2020) |
| Corollary 2 | Prices (+) | Firm & Market | Azar, Schmalz, and Tecu (2018); Park (2020); Aslan (2019); Azar, Raina, and Schmalz (2022) |
| Corollary 3 | Output (−) | Market | Azar, Schmalz, and Tecu (2018) |
| | Concentration (−) | Market | Azar, Schmalz, and Tecu (2018); Azar, Raina, and Schmalz (2022) |
| Prop. 5 | Governance (−) | Firm | Bubb and Catan (2022); Heath, Ringgenberg, Samadi, and Werner (2022) |

---

## Data

### Executive Compensation

The empirical literature uses three leading measures of wealth-performance sensitivity (WPS):

1. **WPS EGL** (Edmans, Gabaix, and Landier 2009): dollar change in CEO wealth for a 100 percentage point change in firm value divided by annual pay. This is the primary measure, appropriate when CEO productivity has a multiplicative effect on firm profits — as in this model, where productivity improvements both improve the profit margin and expand firm output through lower prices.

2. **WPS JM** (Jensen and Murphy 1990): dollar change in CEO wealth per $1,000 increase in firm value. Appropriate when managerial productivity is constant in dollar terms regardless of firm size.

3. **WPS HL** (Hall and Liebman 1998): dollar change in CEO wealth per percentage change in firm value (i.e., effective dollar ownership). Appropriate when managerial productivity is linear in firm size.

Data are from ExecuComp, covering over 3,462 companies including active and inactive firms in the S&P 1500. Accounting and financial controls come from Compustat.

### Ownership

Ownership data come from two sources: Thomson Reuters 13F filings (institutional ownership) and Schwartz, Irani, and Gormley (2021) blockholder data from 13D and 13G filings. The 13F data are augmented by scraping SEC filings to resolve issues with stale and omitted institutional reports. Incorporating both institutional and non-institutional blockholders is important because large blockholders may be correlated with 13F institutional ownership in systematic ways that also correlate with governance outcomes.

### Industry Definitions

The baseline uses four-digit SIC codes from CRSP. Results are also reported for Compustat SIC-4 definitions and the text-based industry classifications of Hoberg and Phillips (2010, 2016). Three-digit SIC codes are used for additional robustness.

### Measuring Common Ownership

The six measures of common ownership used are:

**1. Average profit weight $\overline{\kappa}_i$** (firm-level; value-weighted average of $\kappa_{ij}$ across industry competitors $j$):

$$\overline{\kappa}_i = \frac{1}{\sum_{j \neq i} v_j} \sum_{j \neq i} \kappa_{ij} v_j$$

**2. Cosine similarity $\overline{\cos}_i$** (firm-level; following Backus, Conlon, and Sinkinson 2019):

$$\kappa_{ij} = \cos(\beta_i, \beta_j) \times \sqrt{\frac{IHHI_j}{IHHI_i}}$$

where $\cos(\beta_i, \beta_j)$ is the cosine similarity between ownership vectors and $IHHI_i = \sum_o \beta_{io}^2$ is the investor Herfindahl-Hirschman index. The weighted average of cosine similarities across competitors is:

$$\overline{\cos}_i = \frac{1}{\sum_{j \neq i} v_j} \sum_{j \neq i} \cos(\beta_i, \beta_j) v_j$$

**3. Top 5 measure $\overline{Top5}_i$** (firm-level; model-free): average fraction of competitor shares held by the firm's top five shareholders.

**4. Anton-Polk (AP) measure** (firm-level; following Antón and Polk 2014): total value of stock held by all common shareholders of a firm pair $(i, j)$, scaled by total market capitalization:

$$AP_{ij} = \frac{\sum_o (S^o_i P_i + S^o_j P_j)}{S_i P_i + S_j P_j}$$

**5. Harford-Jenter-Li (HJL) measure** (firm-level; following Harford, Jenter, and Li 2011): relative ownership stake in competitor scaled by the combined stakes:

$$HJL_{ij} = \sum_o \beta_{io} \frac{\beta_{jo}}{\beta_{io} + \beta_{jo}}$$

**6. MHHID** (industry-level; following Bresnahan and Salop 1986; Salop and O'Brien 2000):

$$MHHI = \underbrace{\sum_i s_i^2}_{HHI} + \underbrace{\sum_i \sum_{j \neq i} s_i s_j \frac{\sum_o \gamma_{io} \beta_{jo}}{\sum_o \gamma_{io} \beta_{io}}}_{MHHID}$$

where $s_i$ is firm $i$'s market share and proportional control ($\gamma_{io} = \beta_{io}$) is assumed.

The sample covers 1992–2019 for U.S. publicly-listed firms.

---

## Empirical Analysis

### Empirical Design

The baseline panel specification is:

$$WPS_{ijzt} = \theta \cdot CO_{it} + \xi \cdot X_{ijz_4 t} + \eta_{z_2 t} + \upsilon_i + \varepsilon_{ijzt}$$

where $i$ indexes firms, $j$ indexes managers (CEOs), $z_4$ and $z_2$ denote four- and two-digit industry codes, $X$ is a vector of controls (size, book-to-market, volatility, leverage, executive tenure, institutional ownership), $\eta_{z_2 t}$ are industry-year fixed effects, $\upsilon_i$ are firm fixed effects, and $CO_{it}$ is a measure of common ownership. Rank-transformed common ownership measures are used throughout. Standard errors are clustered two ways at the firm and year level.

Firm fixed effects difference out time-invariant firm characteristics. Industry-year fixed effects control for industry-level trends in common ownership correlated with trends in managerial incentives, ensuring that results are driven by within-firm and within-year variation.

### Panel Regressions

The coefficient on the value-weighted average $\overline{\kappa}_{it}$ is −0.222 (statistically significant at the 1% level). An interquartile range shift (25th to 75th percentile) in firm-level common ownership is associated with a **10.5% reduction** (= $e^{-0.222 \times 0.5} - 1$) in CEO wealth-performance sensitivity (WPS EGL).

For the average CEO in the data (WPS ≈ 20; average flow compensation ≈ $14.8 million in 2019), a 50% increase in firm value increases CEO wealth by $148 million. This number is almost $17 million smaller for a CEO at the 25th percentile of common ownership relative to the 75th percentile.

**Alternative industry definitions.** Results are robust to using Compustat SIC-4 or Hoberg-Phillips definitions. Coefficient estimates remain similar in magnitude and statistical significance across all specifications.

**Alternative common ownership measures.** All six measures of common ownership are significantly negatively related to CEO WPS. An interquartile range move corresponds to decreases of 6.6% to 11.1% in CEO WPS, with consistent signs and significance across all combinations of measures and industry definitions.

**Alternative WPS measures.** Using WPS JM and WPS HL, an interquartile reduction in value-weighted $\kappa$ corresponds to −8.0% reduction in WPS JM and −5.3% reduction in WPS HL, comparable to the −10.5% benchmark.

**Top executives.** The negative association between common ownership and WPS holds for all top executives, not just CEOs, but the effect is weaker. CEOs are principally responsible for firm strategy, so the incentive-reducing effect of common ownership is most pronounced for them.

### Difference-in-Differences Design: S&P 500 Additions

To address the endogeneity of ownership, the paper employs a difference-in-differences design using the addition of a stock $j$ to the S&P 500 as a treatment shock to the common ownership weights of its industry competitors $i$ that are already in the index (following Boller and Scott Morton 2020). The ownership of these treated incumbent competitors is unaffected by the addition; what changes is that their pre-existing shareholders who track the S&P 500 increase their stakes in the newly added rival.

**Identification.** The key feature is that index additions of competitors increase the shareholder profit weights of treated index incumbents but do not change their own ownership structure. Therefore, unlike alternative instruments criticized in the literature (Lewellen and Lowry 2021; Gerakos and Gramacy 2013), this strategy is not confounded by changes in the treated firm's own institutional or block ownership.

**Sample.** In 1994–2019, 289 "true" additions (firms not previously in the S&P 400 or 600) are identified, as opposed to "promotions" from related indices. For each index addition, treated firms are those in the same SIC-4 industry as the added firm that are already S&P 500 members. Control firms are S&P 500 members not in the same industry.

**Specification.** The difference-in-differences specification is:

$$WPS_{ijzt} = \zeta \cdot Treat_{ijz_4} + \theta \cdot Treat_{ijz_4} \cdot Post_{xt} + \xi \cdot X_{ijzPre} + \nu \cdot X_{ijzPre} \cdot Post_{xt} + \upsilon_i + \eta_t + \iota_x + \varepsilon_{ijzt}$$

where $Post_{xt}$ is a dummy equal to 1 for the year of inclusion and all subsequent years for inclusion event $x$, $Treat_{ijz_4}$ is 1 if firm $i$ experiences the index inclusion of an industry competitor, and $\iota_x$ are inclusion fixed effects. The event window is five years before and after inclusion.

**Results.** Following the index inclusion of a direct competitor, the WPS of CEO compensation at treated index incumbent firms declines by **16.4%** (= $e^{-0.179} - 1$) using CRSP SIC-4 industry definitions. This result is robust to alternative industry definitions (Compustat SIC-4: similar; Hoberg-Phillips: −10.1%) and to the inclusion of event fixed effects.

**Pre-trends and placebo.** Pre-inclusion coefficient estimates are consistently insignificant, confirming parallel trends. The negative effect is gradual, increasing in magnitude over time following the competitor's index inclusion. As a placebo, promotions from related indices (S&P 400 or 600) do not significantly increase common ownership and are not followed by significant reductions in WPS, consistent with the hypothesis that an associated ownership change is necessary.

**Additional ruling out of confounds.** The strategy rules out that the results are driven by block ownership, institutional ownership, or passive ownership changes at the treated firm (since the treated firm's own ownership is unaffected). The WPS of newly added firms themselves does not significantly change following their own index addition, ruling out strategic responses by incumbents to changes in the entrant's compensation structure.

---

## Conclusion

This paper examines how shareholder portfolio interests affect optimal managerial incentive contracts under strategic product market competition. The theoretical framework provides a unified explanation for a large set of empirical facts: the sensitivity of top managers' wealth to firm performance is weaker when the firm's largest shareholders are also large shareholders of the firm's competitors. Using panel regressions and a difference-in-differences design, the paper finds consistent and robust empirical support for this prediction.

Firm-level common ownership has a large negative effect on the performance-sensitivity of managerial incentives: an interquartile increase in common ownership reduces CEO WPS by 10.5% in panel regressions and 16.4% in the DID design. The results restrict the kinds of governance channels that are important for common ownership to have effects on firm behavior and product market outcomes — in particular, they are inconsistent with models in which common owners directly control prices or centralize pricing with top managers.

The results also illuminate why there is no paradox between common owners limiting governance interventions (as documented empirically) and the anticompetitive effects of common ownership. In the model, it is precisely the lack of intervention when setting high-powered incentives for top managers that leads to less competitive product market behavior. Weak governance and weak competition are jointly optimal for common owners.

Finally, the results challenge a ubiquitous assumption in industrial organization, organizational economics, and corporate finance: that firms' ownership structures and shareholders' competitive preferences do not affect the structure of managerial incentives. The findings suggest that a firm's behavior and objectives depend on who owns the firm.
