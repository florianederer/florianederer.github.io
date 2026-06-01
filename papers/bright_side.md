# Innovation: The Bright Side of Common Ownership?

**Authors:** Miguel Antón (IESE Business School), Florian Ederer (Boston University), Mireia Giné (IESE Business School), Martin C. Schmalz (University of Oxford Saïd Business School)

**Published in:** *Management Science*, Vol. 71, No. 5, pp. 3713–3733, 2025

**DOI:** [10.1287/mnsc.2024.04363](https://doi.org/10.1287/mnsc.2024.04363)

**How to cite:** Antón, Miguel, Florian Ederer, Mireia Giné, and Martin C. Schmalz (2025). "Innovation: The Bright Side of Common Ownership?" *Management Science* 71(5): 3713–3733.

**JEL Codes:** O31 (Innovation and Invention: Processes and Incentives), L20 (Firm Objectives, Organization, and Behavior), L40 (Antitrust Issues and Policies)

---

## Abstract

A firm has inefficiently low incentives to innovate when other firms benefit from its innovative activity and the innovating firm does not capture the full surplus of its innovations. We provide conditions under which common ownership of firms mitigates this impediment to corporate innovation. Common ownership increases innovation when technological spillovers are sufficiently large relative to product market spillovers. Otherwise, the business stealing effect of innovation dominates and common ownership reduces innovation. Empirically, product market spillovers (as measured by Jaffe/Mahalanobis proximity in product market space) decrease the effect of common ownership on innovation inputs and outputs, whereas technology spillovers (proximity in patent space) increase the effect. The sign and magnitude of the relationship between common ownership and corporate innovation varies considerably across the universe of firms depending on the relative strength of product market and technology spillovers. When product market spillovers are relatively large, an increase from the 25th to the 75th percentile of common ownership is associated with a *decrease* of −8.4% in citation-weighted patents. But when technology spillovers are relatively large, the same increase in common ownership is associated with an *increase* of +12.5% in citation-weighted patents. Our results inform the debate about the welfare effects of increasing common ownership among U.S. corporations.

---

## 1. Introduction

Two secular trends have recently led to a spirited discussion among academics and policy makers regarding the competitiveness of the U.S. economy. First, increasing levels of product market concentration have been accompanied by increasing profitability, a decline of the labor share of income, rising inequality, declining business dynamism, and declining innovation. Second, common ownership has also increased: firms are increasingly commonly owned by a decreasing number of institutional investors.

In this paper we investigate, both theoretically and empirically, how corporate innovation depends on common ownership. In our model, the sign and magnitude of the common ownership effect on corporate innovation vary with the relative importance of technological spillovers and business stealing repercussions of innovative activity.

**Two countervailing forces.** In the presence of technological spillovers, innovation in one firm not only generates benefits in the firm that produced the innovation but also in technologically related firms. This surplus appropriability problem leads to inefficiently low ex-ante incentives to innovate. Common ownership of technologically related firms mitigates this problem to the extent that firms act in the interest of these common owners — common ownership can even render innovative activity profitable that would be unprofitable if it only benefited the innovating firm itself.

However, innovations resulting from R&D expenditures naturally lead to the innovator stealing market share and profits from firms competing in the same or related product markets. When the competitors are predominantly owned by separate groups of shareholders, this procompetitive effect of innovation is desirable for the innovating company's shareholders. But when the same shareholders own both the innovator and its product market competitors, such business stealing is less desirable. Hence, common ownership can reduce the incentives to innovate when the business stealing effect is stronger than the technological spillover effect.

**Illustrative example.** Table 1 (reproduced below) reports the ownership shares of four technology firms — IBM, Intel, Motorola, and Apple — that are technologically related but compete to varying extents in the same product markets.

| Firm pair | Technology proximity | Product market proximity |
|-----------|---------------------|--------------------------|
| IBM – Intel | 0.76 | 0.01 |
| IBM – Motorola | 0.46 | 0.01 |
| IBM – Apple | 0.64 | 0.65 |
| Intel – Apple | 0.47 | 0.00 |
| Motorola – Apple | 0.17 | 0.02 |
| Motorola – Intel | 0.46 | 0.34 |

The sample average technology proximity is 0.038; the sample average product market proximity is 0.015. These four firms also share significant common ownership: BlackRock, Vanguard, and State Street are represented among the top owners of each. Our central theoretical prediction is that the effect of common ownership on innovation depends on firms' relative distances in technology and product market space and can vary both in terms of sign and magnitude.

**Empirical findings.** We find an ambiguous relationship *on average* between common ownership and corporate innovation as measured by innovation inputs (scaled R&D expenditures) and innovation outputs (citation-weighted patents and total stock market value of patents). However, throughout all specifications, innovation is more positively related to common ownership when technological spillovers are higher, whereas more common ownership is associated with less innovation when product market spillovers are greater. The relationship between common ownership and innovation varies considerably across publicly listed firms:

- When product market spillovers are relatively large, an increase from the 25th to the 75th percentile of common ownership is associated with a *decrease* of −8.4% in citation-weighted patents.
- When technology spillovers are relatively large, the same increase in common ownership is associated with an *increase* of +12.5% in citation-weighted patents.

**Relation to prior work.** The most closely related paper is Bloom et al. (2013), who study the effect of product market and technology spillovers on innovation without considering the role of common ownership. López and Vives (2019) theoretically study the effect of common ownership on innovation in a symmetric single-industry model; our model allows for common ownership across the entire economy, with product differentiation, technology spillovers, and common ownership varying across all firm pairs. Our empirical methodology follows Bloom et al. (2013) and Lucking et al. (2019).

---

## 2. Theoretical Framework

### 2.1 Setup

We analyze the role of common ownership and its interplay with product market and technological spillovers in the canonical model of innovation and product market competition pioneered by d'Aspremont and Jacquemin (1988). Our setup extends Bloom et al. (2013) to allow for overlapping ownership and allows common ownership weights, product market spillovers, and technology spillovers to differ across all firm pairs.

### 2.2 Product Market Competition

Consider an economy with $n$ firms that each produce a single differentiated product. Following Singh and Vives (1984) and Häckner (2000), we derive demand from a representative consumer with quadratic utility:

$$U(\mathbf{q}) = A \sum_{i=1}^{n} q_{i} - \frac{1}{2}\left(\sum_{i=1}^{n} q_{i}^{2} + 2 \sum_{i \neq j} a_{ij} q_{i} q_{j}\right)$$

where $q_i$ is the quantity of product $i$, $A > 0$ represents overall product quality, and $a_{ij} \in [0,1)$ is the degree of substitutability between products $i$ and $j$ (product market spillovers). Setting $a_{ii} = 1$ without loss of generality, consumer maximization yields linear inverse demand:

$$p_{i}(\mathbf{q}) = A - q_{i} - \sum_{j \neq i} a_{ij} q_{j}$$

The parameter $a_{ij}$ measures product homogeneity: the larger $a_{ij}$, the more alike the products and the greater the business stealing from expansion.

### 2.3 Innovation

Following d'Aspremont and Jacquemin (1988), Kamien et al. (1992), Leahy and Neary (1997), and López and Vives (2019), we model corporate innovation as decreasing marginal cost. Firm $i$ has marginal cost:

$$c_{i} = \bar{c} - x_{i} - \sum_{j \neq i} \beta_{ij} x_{j}$$

Firm $i$ lowers its marginal cost from $\bar{c}$ by investing in innovation $x_i$ at a cost $\frac{\gamma}{2} x_i^2$. The parameter $\beta_{ij} \in [0,1)$ captures technological spillovers: firm $j$'s innovation reduces firm $i$'s marginal cost to the extent that the firms are technologically related. Profits of firm $i$ are:

$$\pi_{i} = q_{i}\left[A - q_{i} - \sum_{j \neq i} a_{ij} q_{j} - \left(\bar{c} - x_{i} - \sum_{j \neq i} \beta_{ij} x_{j}\right) \right] - \frac{\gamma}{2} x_{i}^2$$

### 2.4 Owners and Objective Function

Following the common ownership literature since Rotemberg (1984), firms maximize a weighted average of their shareholders' portfolio profits. The objective function of firm $i$ is:

$$\phi_{i} = \pi_{i} + \sum_{j \neq i} \kappa_{ij} \pi_{j}$$

where $\kappa_{ij}$ is the weight that firm $i$ places on firm $j$'s profits. Its value depends on the ownership structure; $\kappa_{ij} \in [0,1]$ ranges from separate ownership (0) to perfectly common ownership (1). Unlike the symmetric product market and technology spillover parameters, $\kappa_{ij}$ need not equal $\kappa_{ji}$.

We use the $\kappa$ notation of Backus, Conlon, and Sinkinson (2021), equivalent to the $\lambda$ in Azar, Schmalz, and Tecu (2018) and López and Vives (2019). The equal- or value-weighted average of the profit weights across all other firms is denoted $\bar{\kappa}_{it}$ ("kappa").

### 2.5 Analysis and Comparative Statics

Firm $i$'s first-order conditions with respect to quantity $q_i$ and innovation $x_i$ yield best-response functions:

$$q_{i} = \frac{1}{2} \left[ A - c_i - \sum_{j \neq i} a_{ij} q_{j} - \underbrace{\sum_{j \neq i} \kappa_{ij} a_{ji} q_{j}}_{\text{CO} \times \text{product market spillovers}}  \right]$$

$$x_{i} = \frac{1}{\gamma} \left(q_{i} + \underbrace{\sum_{j \neq i} \kappa_{ij} \beta_{ji} q_{j}}_{\text{CO} \times \text{technology spillovers}} \right)$$

An increase in common ownership $\kappa_{ij}$ has two distinct effects:

1. **Anticompetitive effect (product market spillovers):** Higher $\kappa_{ij}$ reduces $q_i$ through the "CO × product market spillovers" term, and thereby reduces innovation $x_i$. Firm $i$ internalizes the negative profit externality its innovation imposes on product market competitors, reducing business stealing incentives.

2. **Procompetitive effect (technology spillovers):** Higher $\kappa_{ij}$ directly increases innovation through the "CO × technology spillovers" term. Firm $i$ partly internalizes the positive externality of innovation on technologically related firms, increasing innovation.

In matrix notation, defining the product similarity matrix $\mathbf{a}$, the technology spillover matrix $\mathbf{B}$, and the common ownership matrix $\mathbf{K}$, the equilibrium innovation vector is:

$$\mathbf{x^*} = (A-\bar{c}) \left[\gamma \mathbf{K_a}\mathbf{K_\beta}^{-1}-\mathbf{B}\right]^{-1} \cdot \mathbf{1}$$

where $\mathbf{K_a} = \mathbf{a} + \mathbf{K} \circ \mathbf{a}'$ and $\mathbf{K_\beta} = \mathbf{K} \circ \mathbf{B}'$.

**Proposition 1.** Common ownership $\kappa_{ij}$ increases equilibrium firm innovation $x^*_i$ if and only if technological spillovers $\beta_{ij}$ are sufficiently large relative to product market spillovers $a_{ij}$. The effect of $\kappa_{ij}$ on $x_i^*$ is decreasing in $a_{ij}$ and increasing in $\beta_{ij}$:

$$\frac{\partial^2 x_i^*}{\partial \kappa_{ij} \partial a_{ij}} < 0 \qquad \frac{\partial^2 x_i^*}{\partial \kappa_{ij} \partial \beta_{ij}} > 0$$

This proposition explains the variation in empirical findings on common ownership and innovation: depending on the relative strengths of the business stealing effect and the technology spillover effect, common ownership can either decrease or increase corporate innovation. The sign of the effect does not depend on whether firms compete in strategic substitutes or complements — common ownership operates through a direct effect on the objective function rather than a strategic effect.

---

## 3. Data

Unless otherwise stated, all data are from 1985 to 2015. The sample covers publicly listed U.S. corporations.

### 3.1 Measures of Innovation

Innovation inputs are measured by $\ln(1 + R_{it}/\text{SALES}_{it})$ where $R_{it}$ is inflation-adjusted R&D expenditures from Compustat. Because many firms report zero R&D, we add 1 before taking logs, following Branstetter and Sakakibara (2002).

Two measures of innovation output capture scientific and economic value respectively:

**Citation-weighted patents (TCW).** From the Kogan et al. (2017) patent database (augmenting the NBER patent data of Hall, Jaffe, and Trajtenberg 2001):

$$\text{TCW}_{it} = \sum_{j \in P_{it}} \left(1 + \frac{C_j}{\bar{C}_j}\right)$$

where $P_{it}$ is the set of patents issued to firm $i$ in year $t$, $C_j$ is forward citations to patent $j$, and $\bar{C}_j$ is the mean citations to patents granted in the same year. Forward citations measure the scientific quality of innovation.

**Total stock market value of patents (TSM).** The private economic value of innovation (Kogan et al. 2017) is estimated from stock market reactions following patent issuance:

$$\text{TSM}_{it} = \sum_{j \in P_{it}} \xi_j$$

where $\xi_j$ is the estimated abnormal return during the three-day announcement window following the issuance of patent $j$. TSM measures the private economic value fully appropriated by the firm, whereas TCW reflects scientific value.

**Summary statistics** (28,596–28,631 firm-year observations):

| Variable | Mean | Std. Dev. | 10th pct | Median | 90th pct |
|----------|------|-----------|----------|--------|----------|
| R&D Expenditures ($M) | 245.14 | 953.00 | 0.36 | 14.06 | 359.38 |
| ln(1+R&D/Sales) | 0.11 | 0.20 | 0.00 | 0.05 | 0.22 |
| TCW (citation-weighted patents) | 87.45 | 418.96 | 0.00 | 4.01 | 131.43 |
| TSM (patent market value, $M) | 930.73 | 5,867.81 | 0.00 | 3.31 | 933.43 |
| ln(SPILLTECH) | 15.42 | 1.01 | 14.12 | 15.53 | 16.60 |
| ln(SPILLSIC) | 4.49 | 1.78 | 2.32 | 4.67 | 6.65 |
| Capital-labor ratio | 55.22 | 77.16 | 11.05 | 31.45 | 116.95 |
| Sales ($M) | 4,080 | 14,265 | 18 | 288 | 8,652 |
| Institutional Ownership | 0.463 | 0.295 | 0.080 | 0.464 | 0.833 |
| Kappa | 0.208 | 0.167 | 0.050 | 0.161 | 0.426 |

### 3.2 Measures of Technological and Product Market Proximity

Following Bloom et al. (2013) and Lucking et al. (2019), we use SPILLTECH and SPILLSIC as measures of technological and product market spillovers, respectively. SPILLTECH corresponds empirically to $\sum_{j \neq i} \beta_{ij}$ and SPILLSIC corresponds to $\sum_{j \neq i} a_{ij}$ in the model.

**Jaffe distance.** Let $T_i$ be the vector of firm $i$'s patent share across technology classes. The technology spillover pool is:

$$\text{SPILLTECH}_{it} = \sum_{j \neq i} \text{TECH}_{ij} \cdot G_{jt}$$

where $G_{jt}$ is firm $j$'s R&D stock and the Jaffe (1986) uncentered correlation is:

$$\text{TECH}_{ij} = \frac{T_i T'_j}{(T_i T'_i)^{1/2}(T_j T'_j)^{1/2}}$$

Analogously, let $S_i$ be the vector of firm $i$'s sales share across four-digit SIC industries. The product market spillover pool is:

$$\text{SPILLSIC}_{it} = \sum_{j \neq i} \text{SIC}_{ij} \cdot G_{jt}, \qquad \text{SIC}_{ij} = \frac{S_i S'_j}{(S_i S'_i)^{1/2}(S_j S'_j)^{1/2}}$$

Rather than pooling all years, SPILLSIC uses the previous five years of sales data to minimize reverse causality between firm outcomes and product market competition.

**Mahalanobis distance.** We also construct SPILLTECH$^M$ and SPILLSIC$^M$ using the Mahalanobis distance, which allows for spillovers across technology classes and industries. The Mahalanobis SPILLTECH$^M$ measure quantifies spillovers by revealed preference: if two technology classes are often located together in the same firm, the distance between them is smaller. The Mahalanobis SPILLSIC$^M$ is defined analogously.

### 3.3 Measures of Common Ownership

Ownership data come from Thomson Reuters 13F filings (institutions with at least $100M assets under management), augmented by scraping SEC 13F filings following Ben-David et al. (2016). We also use Execucomp for officer and board member holdings.

Our main measure of common ownership is the equal- or value-weighted average kappa across all firms:

$$\bar{\kappa}_{it} = \frac{1}{n-1}\sum_{j \neq i} \kappa_{ij,t} \quad \text{or} \quad \bar{\kappa}_{it} = \frac{1}{\sum_{j \neq i} \omega_{jt}} \sum_{j \neq i} \kappa_{ij,t} \omega_{jt}$$

where $\omega_{jt}$ is the market capitalization of firm $j$ in year $t$. We exclude observations where $\bar{\kappa}_{it} > 1$, which are indicative of data errors, following Backus, Conlon, and Sinkinson (2021). Average kappa in the sample is 0.208 (interquartile range: 0.092 to 0.277).

### 3.4 Other Control Variables

Controls include $\ln(\text{SALES}_{it})$ (inflation-adjusted), $\ln(K_{it}/L_{it})$ (capital-labor ratio: log of plant, property, and equipment divided by employees), and the share of total institutional ownership.

---

## 4. Empirical Analysis

### 4.1 Empirical Methodology

Our baseline panel regression is:

$$\text{INNOVATION}_{it} = \alpha_1 \cdot \text{CO}_{it} + \alpha_2 \cdot \text{SPILLSIC}_{it} + \alpha_3 \cdot \text{SPILLTECH}_{it}$$
$$+ \alpha_4 \cdot \text{CO}_{it} \cdot \text{SPILLSIC}_{it} + \alpha_5 \cdot \text{CO}_{it} \cdot \text{SPILLTECH}_{it}$$
$$+ \alpha_6 \cdot X_{it} + \sum_x \xi_x \cdot \eta_x + \varepsilon_{it}$$

where $X_{it}$ is the vector of control variables and $\eta_x$ with $x \in \{i, t\}$ are firm and year fixed effects. Standard errors are clustered at the firm level. We estimate OLS for scaled R&D and stock market patent value; negative binomial count data models for citation-weighted patents (with pre-sample mean as in Blundell et al. 1999, Bloom et al. 2013).

The principal coefficients of interest are $\alpha_4$ and $\alpha_5$, which measure how the relationship between common ownership and innovation varies with product market and technology spillovers.

### 4.2 R&D Expenditures

Table 2 reports OLS results for $\ln(1 + R_{it}/S_{it})$ across six specifications: columns 1–4 use Jaffe proximity measures; columns 5–6 use Mahalanobis measures.

Key findings:
- **Column 2:** Common ownership is negatively correlated with R&D ($-0.00151^{**}$), but the magnitude is small: increasing kappa from 0 to 1 is associated with only a −0.15% (Jaffe) or −0.12% (Mahalanobis) decrease in sales-adjusted R&D.
- **Columns 3–6:** Interaction terms with technology spillovers are consistently positive ($0.00247^{**}$, $0.00486^{***}$), while interactions with product market spillovers are consistently negative ($-0.00111^{**}$, $-0.00224^{**}$).

In aggregate, the countervailing technology and product market spillover forces essentially cancel each other out — but this masks significant heterogeneity: for about half of firms (those with high technology and low product market spillovers), the relationship is positive, while for the other half it is negative.

### 4.3 Citation-Weighted Patents (TCW)

Table 3 reports negative binomial results for TCW.

Key findings:
- **Column 2:** On average, citation-weighted patents are weakly positively correlated with common ownership (0.0476), but statistically insignificant.
- **Columns 3–6:** Once interaction terms are included, the coefficient on common ownership is consistently negative ($-6.085^{***}$). As predicted by theory, this negative relationship is larger in magnitude when product market spillovers are higher ($-0.237^{***}$), but smaller or positive when technology spillovers are larger ($+0.465^{***}$).

**Quantitative heterogeneity:**
- For a firm at the 75th percentile of technology spillovers (SPILLTECH = 16.13) and 25th percentile of product market spillovers (SPILLSIC = 3.53), an interquartile range increase in common ownership (0.092 to 0.277) is associated with a **+12.5%** increase in citation-weighted patents.
- The same increase in common ownership implies a **−8.4%** decrease for a firm at the 25th percentile of technology spillovers and 75th percentile of product market spillovers.

Figure 1 (in the paper) plots the full distribution of firm-specific implied coefficient estimates, showing that the relationship between common ownership and TCW ranges from strongly negative to strongly positive across the universe of publicly listed firms.

### 4.4 Total Stock Market Value of Patents (TSM)

Table 4 reports OLS results for $\ln(1 + \text{TSM}_{it})$.

Key findings:
- **Column 2:** On average, patent market value is significantly *positively* correlated with common ownership ($0.581^{***}$).
- **Columns 3–6:** Once interaction terms are included, the coefficient on common ownership is consistently negative ($-2.779^{***}$), with technology spillovers again increasing the common ownership effect ($+0.206^{***}$). The interaction with product market spillovers is positive but statistically insignificant for TSM, in contrast to the R&D and TCW results.
- **Institutional ownership** is positive and significant ($0.367^{**}$), consistent with Aghion et al. (2013).

Figure 2 (in the paper) shows the distribution of firm-specific effects: in contrast to TCW, the vast majority of implied coefficient estimates for TSM are positive, with only a small fraction negative.

### 4.5 Causal Interpretation

The finding of small effects on R&D inputs but economically large effects on R&D outputs is consistent with Li et al. (2020), who find that common ownership by venture capitalists in the pharmaceutical industry reduces duplication and increases innovation efficiency.

On endogeneity: ownership is taken as exogenous in the theoretical model, whereas the data reflect portfolio choices. However, it is difficult to formulate a simple economic model in which active investors' preferences for certain ownership patterns (overweighting industry competitors vs. technologically related firms) would be correlated with preferences for high or low innovation for reasons unrelated to portfolio considerations. The economic model provides a significantly simpler and intuitive explanation for the observed empirical patterns.

---

## 5. Conclusion

We show that common ownership can increase innovation when technological spillovers are sufficiently large relative to product market spillovers. On the other hand, common ownership can also decrease innovation because common owners would like to discourage business stealing between commonly owned companies that compete in product markets. The ambiguity of the theoretical prediction poses an interesting empirical question about the sign and magnitude of the effect.

Consistent with our theoretical predictions, we find that common ownership has a positive effect on innovation inputs and outputs whenever innovation spillovers to other firms are relatively large compared to the firms' distance in the product market space, and a negative effect if product market spillovers dominate. The relationship between common ownership and innovation varies considerably across publicly listed firms depending on the relative strength of these two forces.

Our findings inform an active debate on whether welfare-enhancing effects of common ownership outweigh the previously documented negative effects on firms' incentives to compete. Because a positive effect on innovation — modeled here as an efficiency increase — is a *necessary* condition for common ownership to positively affect welfare (López and Vives 2019), findings of positive innovation effects are a necessary ingredient in the argument against regulatory interventions on horizontal common ownership links that have competitive effects.

The more nuanced insight is that antitrust and innovation policy should distinguish between common ownership of horizontal competitors and common ownership of technologically (or vertically) related firms. Previous literature indicates that the former weakens competition and, as we show, also reduces innovation. Our theoretical analysis and empirical results suggest that the latter promotes innovation and potentially even increases total welfare.

---

## Appendix: Proofs and Additional Theoretical Results

The appendix provides formal proofs of Proposition 1, including the result for Bertrand competition (prices as strategic complements). The main results regarding the sign of the common ownership effect on innovation are essentially identical under Bertrand and Cournot competition, because common ownership operates through a direct effect on the objective function rather than through strategic responses of other firms.
