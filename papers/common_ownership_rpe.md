# Common Ownership and Relative Performance Evaluation

**Miguel Antón** (IESE Business School)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Mireia Giné** (IESE Business School, ECGI, and WRDS)
**Martin Schmalz** (University of Oxford)

*Working Paper*

---

## Abstract

We show theoretically and empirically that executives are paid less for their own firm's performance and more for their rivals' performance if an industry's firms are more commonly owned by the same set of investors. Higher common ownership also leads to higher unconditional total pay. We exploit quasi-exogenous variation in common ownership from a mutual fund trading scandal to support a causal interpretation. These findings challenge conventional assumptions in the corporate finance literature about the objective function of the firm.

**JEL Codes:** G30, G32, D21, J31, J41.

---

## Theoretical Framework

### Product Market Competition

Two firms are labeled 1 and 2. At stage 1, owners write contracts with managers. At stage 2, managers engage in differentiated Cournot or Bertrand competition. Profits of firm $i$ are:

$$\pi_i = q_i(A - bq_i - aq_j - c), \quad b > a > 0.$$

The linear contract offered to manager $i$ is:
$$w_i = k_i + \alpha_i \pi_i + \beta_i \pi_j,$$

where $\alpha_i$ is the incentive slope on own firm profits, $\beta_i$ is the incentive slope on rival firm profits (the RPE component), and $k_i$ is a fixed payment satisfying the individual rationality constraint.

### Ownership Structure and the Objective Function

Two owners, A and B, are symmetric: A owns share $x \geq 1/2$ of firm 1 and $1-x$ of firm 2; B owns the mirror image. The parameter $1-x$ measures the degree of common ownership. The majority owner of firm $i$ maximizes:

$$\max_{k_i, \alpha_i, \beta_i} x(\pi_i - w_i) + (1-x)(\pi_j - w_j)$$

subject to the individual rationality constraint $w_i \geq w_i'$ and the manager's optimal competitive response.

### Key Theoretical Results

**B1 — Separate Ownership ($1-x = 0$):** Under completely separate ownership, the equilibrium incentives are:
- Cournot: $\beta_i^* = -\alpha_i^* \frac{a}{2b+a} < 0$
- Bertrand: $\beta_i^* = \alpha_i^* \frac{e}{2d-e} > 0$

The sign difference reflects the modes of strategic interaction: with strategic substitutes (Cournot), each owner punishes their manager for rivals' profits; with strategic complements (Bertrand), each owner rewards their manager for rivals' profits. In both cases, this is classical RPE motivated by strategic product market considerations.

**B2 — Perfectly Common Ownership ($1-x = 1/2$):** Under equal and thus perfectly common ownership, equilibrium incentives are $\beta_i^* = \alpha_i^* > 0$ under both Cournot and Bertrand competition. Owners design managerial incentives that place equal weight on own and rival profits, leading to the monopoly equilibrium.

**B3 — Central Result (Proposition):** As common ownership $1-x$ increases from 0 to $1/2$, the incentive slope on rival firm profits $\beta_i^*$ **increases unambiguously** under both Cournot and Bertrand competition. This prediction holds for all intermediate cases of ownership.

Under Cournot, $\beta^*$ increases from $-\alpha^* \frac{a}{2b+a}$ to $\alpha^*$; under Bertrand, it increases from $\alpha^* \frac{e}{2d-e}$ to $\alpha^*$. The sign of the change is always positive, providing an **unambiguous prediction** independent of the mode of competition.

**Higher common ownership also leads to higher unconditional pay:** In the full model with risk-averse managers, common ownership implies it is optimal not to filter out common industry shocks. This makes compensation riskier, and risk-averse managers with a given outside option therefore demand higher baseline pay as compensation for the additional risk.

---

## Measuring Common Ownership

The empirical analysis uses the modified Herfindahl-Hirschman Index (MHHID) to measure common ownership concentration across industries:

$$MHHI_D = \sum_{j \neq k} \frac{\sum_s \beta_{js} \beta_{ks}}{\sum_{j} \left(\sum_s \beta_{js}^2\right) q_j / q_k}$$

where $\beta_{fs}$ denotes the share of firm $f$ owned by investor $s$. Total market concentration is $MHHI = HHI + MHHID$. This measure is market-share-free, making it robust to concerns about endogeneity of market shares.

---

## Data and Sample

The analysis covers S&P 1,500 firms from 1993 to 2014. Key data sources:
- **Executive compensation:** Execucomp (total pay including value of stock and option grants).
- **Ownership:** Thomson Reuters mutual fund holdings (13-F filings).
- **Industries:** SIC codes and Hoberg-Phillips product-similarity classifications.
- **Identification instrument:** Mutual fund trading scandal of 2003, which affected funds jointly holding 25% of total mutual fund assets, causing exogenous changes in common ownership among their portfolio firms.

Both BlackRock and Vanguard are among the top five shareholders of almost 70 percent of the largest 2,000 publicly traded U.S. firms; twenty years ago that number was zero percent for both firms. Ownership-adjusted market concentration is frequently twice as large as suggested by traditional HHI indices.

---

## Empirical Results

### Panel Regressions

Regressing total executive pay on own firm's performance, rival firms' performance, market concentration (HHI), common ownership (MHHID), and their interactions:

**Finding 1:** Higher levels of common ownership (MHHID) are associated with **lower pay-for-own-performance sensitivity** (lower $\alpha$). Managers in more commonly owned industries receive less pay for their own firm's performance.

**Finding 2:** Higher common ownership is associated with **higher pay-for-rival-performance sensitivity** (higher $\beta$). Managers receive more pay tied to industry-wide rather than own-firm performance.

**Finding 3:** Higher common ownership is associated with **higher unconditional CEO pay**. Performance-insensitive pay packages are more prevalent in commonly owned industries.

These relationships hold across time-series variation (as industries become more commonly owned, their managers receive weaker own-firm incentives and stronger industry-wide incentives) and cross-sectional variation.

Results are robust to:
- Alternative industry definitions including Hoberg-Phillips product-similarity classifications
- Using the managers' accumulated wealth stock (including stock and options) rather than flow of total pay
- Market-share-free measures of common ownership (MHHID)

### Causal Identification: The 2003 Mutual Fund Trading Scandal

The main endogeneity concern is that common ownership is endogenously determined by stock prices or that other factors jointly determine ownership structure and pay packages.

A plausibly exogenous variation in ownership is exploited from the **2003 mutual fund trading scandal**, which caused large outflows from implicated funds and disrupted the common ownership links they had created among their portfolio firms. Firms whose industries had common ownership links through the affected funds experienced exogenous reductions in common ownership.

Using this scandal as an instrument:
- Firms whose industries experienced reductions in common ownership from the scandal show **increases** in pay-for-own-performance sensitivity.
- Firms whose industries experienced increases in common ownership show **decreases** in pay-for-own-performance sensitivity.

These IV results corroborate the findings from panel regressions and support a causal interpretation: common ownership causes weaker incentives to compete aggressively.

---

## Conclusion

Common ownership across competing firms in an industry — concentrated among a few large diversified asset managers — leads to two systematic distortions in executive compensation:

1. **Weakened own-firm incentives:** Managers are paid less for their own firm's performance as common shareholders prefer less aggressive competition across their portfolio firms.

2. **Strengthened industry incentives:** Managers are paid more for industry performance, aligning their objectives with the portfolio value of common shareholders rather than single-firm value maximization.

These findings challenge the standard assumption in corporate finance that shareholders unanimously want managers to maximize their firm's own value. The evidence suggests that broadly diversified investors' endorsement of high, performance-insensitive compensation packages reflects their anticompetitive economic interests — not inattention or lack of power.
