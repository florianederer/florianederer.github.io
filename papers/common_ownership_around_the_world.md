# Common Ownership Around the World

**Miguel Antón** (IESE Business School)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Mireia Giné** (IESE Business School, ECGI, and WRDS)
**Guillermo Ramirez-Chiang** (IESE Business School)

*Working Paper*

---

## Abstract

We study common ownership in 49 countries from 2005 to 2019, covering economies that account for 86% of global GDP. Common ownership is pervasive and rising around the world: average pairwise implied profit weights ($\kappa$) more than doubled in the median country over our sample period and more than tripled in the United States. Common ownership exhibits a steep size gradient — highest among the largest firms and rising fastest at the top of the firm size distribution — a pattern we observe consistently across all countries and regions. We show that the rise of common ownership stems not just from more institutional investment but from its increasing concentration among a few megaproviders of capital such as the Big Three (BlackRock, Vanguard, State Street). Even outside the United States, where non-Big Three investors remain important, the Big Three account for the largest share of the increase in common ownership in most countries. We also investigate how common ownership is related to legal, institutional, and market characteristics such as investor protection laws, competition laws, mandatory ESG disclosure, and labor market frictions across firms and countries.

---

## Measuring Common Ownership

### Profit Weights

The theoretical foundation is the common ownership hypothesis, under which firm $f$'s manager maximizes a weighted sum of profits across all firms:

$$\phi_f = \pi_f + \sum_{g} \kappa_{fg} \pi_g$$

where $\kappa_{fg} \geq 0$ captures the relative weight firm $f$ places on firm $g$'s profits. The implied profit weight is defined as:

$$\kappa_{fg} = \frac{\sum_{s} \gamma_{fs} \beta_{gs}}{\sum_{s} \gamma_{fs} \beta_{fs}}$$

where $\beta_{fs}$ and $\gamma_{fs}$ are the cash flow rights and control rights that shareholder $s$ has in firm $f$, and $\beta_{gs}$ denotes shareholder $s$'s cash flow rights in firm $g$. Under the "one share, one vote" assumption, $\gamma_{fs} = \beta_{fs}$.

A higher $\kappa_{fg}$ implies greater internalization of rival profits and therefore softer product market competition. The paper uses three variants:
- **Universal ownership (UO):** all firm pairs within a country
- **Intra-industry common ownership (CO):** firm pairs in the same country and industry
- **Inter-industry common ownership:** firm pairs in the same country, different industries

### Variance Decomposition

Under the one-share-one-vote assumption, the profit weight decomposes multiplicatively:

$$\log \kappa_{fg} = \underbrace{\log \cos(\boldsymbol{\beta}_f, \boldsymbol{\beta}_g)}_{\text{overlapping ownership}} + \underbrace{\log \sqrt{\frac{\mathrm{IHHI}_g}{\mathrm{IHHI}_f}}}_{\text{relative IHHI}}$$

where $\cos(\boldsymbol{\beta}_f, \boldsymbol{\beta}_g) = \bigl(\sum_s \beta_{fs}\beta_{gs}\bigr) / \sqrt{\mathrm{IHHI}_f \cdot \mathrm{IHHI}_g}$ is the cosine similarity between the two ownership vectors and $\mathrm{IHHI}_f = \sum_s \beta_{fs}^2$ is the investor Herfindahl-Hirschman Index. The covariance between the two log components is mechanically zero, so the variance of $\log \kappa_{fg}$ decomposes additively.

---

## Data

The analysis uses the Thomson Reuters Global Ownership Database, which covers shareholdings by institutional investors, pension funds, insurance funds, individual and family blockholders, and government entities. The database draws on 13-F filings, stock exchange registers, regulatory filings, and company disclosures. A key advantage over databases that cover only 13-F institutions is the accurate capture of large individual and family stakes — critical for non-US firms where family ownership is common.

**Sample construction:** The final sample comprises 61,649 unique firms from 49 countries spanning 2005–2019, representing 86% of world real GDP. Ownership data start from 22,100 firms in 2005Q1 and increase to 35,945 by 2019Q4. Median ownership coverage (fraction of shares outstanding captured) remains above 58% throughout.

Multi-class share firms are excluded to avoid mismeasurement of control rights. Holdings by Chinese government-linked entities are consolidated across direct state institutions and state-owned enterprises. Fund families are aggregated at the fund family level, accounting for major asset management mergers (e.g., BlackRock-BGI in 2009).

---

## Geographic Variation and Time Patterns

### Cross-Country Levels (2019)

Common ownership is a feature of equity markets around the world but highly unequal:

- **United States:** Average pairwise $\kappa = 0.154$, by far the highest in the world — two to four times larger than any other country
- **Second tier:** Ireland (0.111), China (0.096), South Africa (0.079)
- **Western Europe:** Generally 0.02–0.06, with Northern European countries (Netherlands, Nordic economies) higher than Southern European countries
- **Most other countries:** Substantially lower, particularly in Southern Europe, Latin America, and the Middle East

Intra-industry common ownership is systematically higher than inter-industry common ownership in nearly every country. For the United States, intra-industry, inter-industry, and universal ownership are roughly similar in magnitude, reflecting the extraordinary breadth of overlapping shareholding by large passive investors across all sectors.

### Time Trends (2005–2019)

Common ownership is rising in virtually every major economy:

- **United States:** Average $\kappa$ for all public firms more than tripled from approximately 0.05 in 2005 to 0.16 in 2019; for top-tercile firms it reached 0.511 by end of sample
- **Euro Area:** Average $\kappa$ for top-tercile firms rose from under 0.015 to over 0.08; the sharpest increase followed the BlackRock-BGI merger in late 2009
- **Japan:** Common ownership rose abruptly after 2014, driven by the Bank of Japan's ETF purchasing program under the Quantitative and Qualitative Monetary Easing (QQE) program, particularly after the 2016 rule change that shifted allocations toward TOPIX ETFs
- **UK, China, South Africa:** Already at high levels; growth was more muted, partly because these countries started from elevated bases

**Global aggregate:** Universal ownership among the top decile of firms worldwide doubled between 2005 and 2019, with similar increases when U.S. firms are excluded — confirming that the rise is a genuinely global phenomenon rather than a purely American development.

### Variance Decomposition

Overlapping ownership (cosine similarity of the two ownership vectors) dominates the variance of $\kappa$ in every country and dimension, accounting for at least 75% of cross-sectional variance in almost every country and exceeding 85% in the time-series dimension for most economies. This contrasts with earlier work focused exclusively on S&P 500 firms, where relative IHHI (investor concentration) accounted for a larger share. The difference reflects inclusion of blockholders and insiders who raise IHHI levels but reduce variation in relative IHHI. The conclusion is that the secular rise in common ownership is a story of expanding portfolio overlap — breadth of institutional holdings — rather than deepening investor concentration within individual firms.

---

## Size Gradient

A remarkably consistent pattern across all 49 countries is that common ownership is highest among the largest firms and rises fastest at the top of the firm size distribution:

- Average pairwise $\kappa$ is roughly **three times higher** for above-median firms than for the full firm universe
- The gap widens further for top-tercile firms and is particularly pronounced in developed capital markets
- U.S. top-tercile firms: $\kappa = 0.511$ in 2019Q4
- Euro Area top-tercile firms: $\kappa = 0.048$; Japan: $\kappa = 0.110$; UK: $\kappa = 0.158$

This pattern connects directly to the broader rise of megafirms and superstar firms in product markets: the same structural forces that drive market share concentration also make the largest firms the primary focal points of overlapping institutional ownership. As a consequence, estimates of common ownership based solely on major stock index constituents may substantially understate its level for the very largest firms while potentially overstating it for the median publicly listed firm.

---

## The Role of the Big Three

### Dominance in the United States

The Big Three (BlackRock, Vanguard, State Street) became the largest shareholder in nearly **40% of U.S. public companies** by 2019, up from under 3% in 2005. Their contribution to average $\kappa$ among all U.S. firms rose from approximately 0.008 in 2005 to 0.135 by 2019; for top-tercile firms it exceeds 0.45. The share of non-Big Three institutional investors as largest owners declined from 65% in 2005 to 40% in 2019, with a sharp drop following the BlackRock-BGI merger in 2009.

### Global Footprint

Despite holding much smaller individual stakes outside the United States, the Big Three contribute disproportionately to the increase in common ownership globally due to the extraordinary breadth of their portfolios:

- In the Euro Area the combined Big Three stake is approximately 2.43% of the average firm's equity, yet their contribution to $\kappa$ accounts for most of the observed time-series increase
- The increase in $\kappa$ in Germany, France, and Australia is almost entirely attributable to rising Big Three holdings
- In Japan, both Big Three and non-Big Three (Nomura, Nikko, Daiwa) contribute in roughly equal parts
- In the UK, Big Three increases have been mostly offset by declines in non-Big Three contributions

The key insight is that the contribution of an investor to $\kappa$ is driven by the **network structure** of its portfolio — the number of firms in which it holds even modest stakes — rather than the depth of its control over any single firm. Even 0.5% stakes across thousands of firms generate a dense web of overlapping ownership.

### Ownership Types Globally

- **Individual/family:** Remains important in Italy, Spain, India, France; less than 10% of firms in Norway and Indonesia (where sovereign wealth dominates)
- **Government:** Central to China (2,598 firms under state-linked ownership), South Africa (Public Investment Corporation), India, and Italy
- **Non-Big Three institutional:** Dominant in Japan (Nomura, Nikko, Daiwa), Germany (Norges Bank, DWS, Amundi), France (Amundi, MFS)
- **Geographic proximity matters:** U.S. investors dominate in Canada, Mexico, UK, and Ireland; Europe has significant cross-border institutional ownership among smaller economies

---

## Case Study: Japan's ETF Purchasing Program

Japan illustrates how a specific policy shock can generate a rapid and well-identified increase in common ownership. The Bank of Japan (BoJ) introduced its ETF purchasing program in October 2010 as part of the Comprehensive Monetary Easing (CME) program, initially targeting Nikkei 225 and TOPIX index ETFs.

Key milestones:
- **April 2013:** Governor Kuroda replaced CME with Quantitative and Qualitative Monetary Easing (QQE), sharply expanding ETF purchases — common ownership began rising
- **November 2014:** JPX-Nikkei 400 ETFs added to the purchasing program
- **September 2016:** BoJ doubled the ETF purchase amount (from ¥3 trillion to ¥5.7 trillion per year) and shifted allocation substantially toward TOPIX, which is capitalization-weighted and broader than the price-weighted Nikkei 225 — universal ownership for top-tercile Japanese firms accelerated sharply after this date

The BoJ's purchases channeled through the "Japanese Big Three" ETF providers (Nomura Asset Management, Nikko Asset Management, Daiwa Asset Management) and through BlackRock Japan, all of which saw their holdings increase markedly beginning in 2013. This structural shift explains why Japan's universal ownership trend is delayed relative to the U.S. and Europe and why it accelerated precisely at the 2016 inflection point.

---

## Institutional Determinants of Common Ownership

The estimating equation relates firm-level average $\kappa$ to institutional and legal characteristics:

$$\bar{\kappa}_{f,c,q} = \alpha_0 + \beta' X + \delta' Z_{f,c,q} + \gamma' GDP_{c,y} + \alpha_r + \alpha_{p4} + \alpha_q + \epsilon_{f,c,q}$$

where $\bar{\kappa}_{f,c,q} = \frac{1}{N_{c,q}-1}\sum_{g \neq f} \kappa_{fg,c,q}$ is the equal-weighted average profit weight that firm $f$ places on all other firms in country $c$ in quarter $q$; $Z_{f,c,q}$ includes firm-level controls (top-5 ownership, log market cap, log firm age); $GDP_{c,y}$ is log GDP per capita; regional, four-digit industry, and year-quarter fixed effects are included.

### Firm-Level Drivers

- **Market capitalization** is by far the strongest predictor: larger firms have substantially higher $\kappa$
- **Big Three ownership** is positively associated with $\kappa$, even after controlling for size
- **Ownership concentration (C5 index)** is negatively associated with $\kappa$: blockholders crowd out diversified overlapping institutional investors
- **Individual/family and foreign investor ownership** is negatively associated with $\kappa$; government ownership is positively associated

### Antitrust Laws

Using the Competition Law Index (CLI) of Bradford and Chilton (2018), which ranges from 0 (weak) to 1 (strong):

- An increase in the CLI is associated with a **–0.030** reduction in universal ownership (10% significance)
- **Abuse of dominance** provisions: –0.036 to –0.037 decrease in UO and CO (5% significance)
- **Anticompetitive agreements** provisions: –0.038 and –0.037 decrease in UO and CO (5% and 1% significance)
- **Merger control** provisions: +0.029 increase in CO (1% significance), suggesting that common ownership may function as a partial substitute for mergers in jurisdictions with strong merger restrictions

Excluding the U.S. from the sample, only abuse of dominance provisions remain statistically significant.

### Market Entry Regulations

Using World Bank Doing Business data:

- A 1-unit increase in log(number of procedures to start a business): +0.023 increase in UO and +0.024 in CO (5% and 1% significance)
- A 1-unit increase in log(days required): +0.011 increase in both UO and CO (10% significance)

Higher regulatory barriers to entry are associated with higher common ownership, consistent with common ownership reducing competitive pressures (the "quiet life" hypothesis) or with incumbent investor networks being reinforced when entry is restricted.

### Labor Laws

Using employment regulation indices from Botero, Djankov, La Porta, Lopez-de-Silanes, and Shleifer (2004):

- **Employment protection laws:** –0.024 decrease in UO (significant); restricting layoffs may limit investor governance power
- **Collective labor relations (union power):** –0.055 decrease in UO (5% significance)
- **Social security provisions:** positively associated but statistically insignificant

Stronger labor protections are associated with lower common ownership, consistent with Roe (2006) and Mueller and Philippon (2011): laws making workforce management costly reduce ownership diffusion and investor influence.

### Investor Protection

Using the Anti-Self-Dealing Index and Creditor Rights Index from Djankov, La Porta, Lopez-de-Silanes, and Shleifer (2008):

- **Anti-Self-Dealing Index:** +0.040 increase in UO (significant); stronger protection from controlling shareholder expropriation creates an environment where dispersed but overlapping institutional ownership can flourish
- **Ex-ante private self-dealing:** +0.035 (significant)
- **Ex-post self-dealing** provisions and creditor rights: statistically insignificant

### ESG Disclosure

Mandatory ESG disclosure requirements are generally weakly associated with common ownership, with one exception:
- **Government-mandated ESG disclosure:** –0.016 to –0.019 decrease in UO and CO (significant); may deter ownership concentration by increasing compliance costs or by substituting informationally for the monitoring role of common ownership

### Political Institutions

Using World Bank Worldwide Governance Indicators:
- **Poor regulatory quality:** +0.030 increase in UO and CO (significant); in countries with weak regulatory institutions, ownership may be more concentrated due to reduced competition enforcement and weaker shareholder protections
- **Political instability, corruption:** statistically insignificant

---

## Conclusion

This paper provides the first comprehensive global documentation of common and universal ownership across 61,649 publicly listed firms in 49 countries from 2005 to 2019. Four principal conclusions emerge:

1. **Common ownership is a global and accelerating phenomenon.** Average pairwise $\kappa$ more than doubled in the median country between 2005 and 2019, and more than tripled in the United States. The U.S. remains a clear outlier at levels two to four times higher than the next highest countries.

2. **The rise is driven by increasing concentration within institutional investing.** The Big Three became the largest shareholder in nearly 40% of U.S. companies by 2019, up from under 3% in 2005. Despite holding much smaller individual stakes outside the U.S., the Big Three account for the single largest contribution to the rise in common ownership in most countries due to the extraordinary breadth of their portfolios.

3. **Common ownership is disproportionately concentrated among the largest firms.** Universal and common ownership are on average three times higher for above-median firms than for the full firm universe, with the gap widening for top-tercile firms. This size gradient is remarkably consistent across all 49 countries and closely related to the rise of superstar firms.

4. **Cross-country variation is systematically related to institutional and legal characteristics.** Stronger antitrust enforcement and labor protections are associated with lower common ownership; more burdensome market entry regulations, stronger investor protection laws, and weaker political institutions are associated with higher common ownership; government-mandated ESG disclosure is associated with lower ownership concentration.

These findings carry significant implications for policymakers and competition authorities. The global and accelerating rise of common ownership — concentrated among the largest firms and driven by a small number of dominant passive investors — warrants careful scrutiny of its potential anticompetitive effects. At the same time, the substantial cross-country variation and its systematic relationship with legal and institutional characteristics suggests that policy design can meaningfully shape the prevalence and structure of common ownership.
