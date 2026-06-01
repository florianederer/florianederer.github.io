# A Tale of Two Networks: Common Ownership and Product Market Rivalry

**Florian Ederer**¹ and **Bruno Pellegrino**²

¹ Boston University, CEPR, ECGI, and NBER. florian.ederer@gmail.com  
² Columbia University, CESifo, and UChicago Stigler Center. bp2713@columbia.edu

---

**Published in:** *Review of Economic Studies*, Vol. 93, No. 3, pp. 1746–1788, 2026

**DOI:** [10.1093/restud/rdaf057](https://doi.org/10.1093/restud/rdaf057)

**How to cite:** Ederer, Florian and Bruno Pellegrino (2026). "A Tale of Two Networks: Common Ownership and Product Market Rivalry." *Review of Economic Studies* 93(3): 1746–1788. https://doi.org/10.1093/restud/rdaf057

---

## Abstract

We study the welfare implications of the rise of common ownership in the United States from 1995 to 2021. We build a general equilibrium model with a hedonic demand system in which firms compete in a network game of oligopoly. Firms are connected through two large networks: the first reflects ownership overlap, the second product market rivalry. In our model, common ownership of competing firms induces unilateral incentives to soften competition and the magnitude of the common ownership effect depends on how much the two networks overlap. We estimate our model for the universe of U.S. public corporations using a combination of firm financials, investor holdings, and text-based product similarity data. We perform counterfactual calculations to evaluate how the efficiency and the distributional impact of common ownership have evolved over time. Under the assumption that firms maximize a share-weighted average of their shareholders' income, we find that the welfare cost of common ownership, measured as the ratio of deadweight loss to total surplus, has increased about ninefold between 1995 and 2021. Under alternative assumptions about corporate governance, the deadweight loss of common ownership ranges between 3.5% and 13.2% of total surplus in 2021. The rise of common ownership has also led to a significant reallocation of surplus from consumers to producers.

**JEL Codes:** D43, D85, E23, L16, G23, G34

**Keywords:** common ownership, corporate governance, networks, institutional investors, oligopoly

---

## 1. Introduction

Over the last three decades the ownership of corporate equity in the United States has become increasingly concentrated in the hands of a few large institutional investors (Ben-David, Franzoni, and Moussawi 2016), a trend known as the rise of common ownership (Azar 2012; Gilje, Gormley, and Levit 2020; Backus, Conlon, and Sinkinson 2021). Common ownership describes a structure in which large investors hold significant stakes in several competing firms. The tremendous increase of common ownership has raised concerns among policymakers because it may lessen firms' economic incentives to aggressively compete against each other.

If firms make strategic decisions to maximize the profits accruing to their investors, common ownership can lead firms to (partially) internalize the effect of aggressive market decisions on their competitors' profits. This may induce firms to produce lower quantities or to charge higher prices, ultimately leading to deadweight and consumer surplus losses.

Concerns about the harm of common ownership are supported by a long-standing and growing academic literature, starting with Rubinstein (1983) and Rotemberg (1984), that studies oligopolistic behavior in the presence of common ownership. In response to the secular rise of common ownership and the concurrent surge of empirical research on its anticompetitive effects (see Schmalz 2018 for a recent survey), antitrust authorities and financial regulators around the world have begun studying policy measures to address them.

Despite the enormous academic and policy interest in common ownership, as of today, there has been no attempt to quantify its aggregate welfare impact. This paper fills that gap.

We develop a general equilibrium model in which granular, commonly-owned firms compete in a network game of oligopoly. Building on the rich literature on linear-quadratic network games (Ballester, Calvo-Armengol, and Zenou 2006; Ushchev and Zenou 2018; Galeotti et al. 2020), firms are connected through two large networks: the first reflects ownership overlap, the second product similarity.

We estimate the model using data on firm financials, text-based product similarity (Hoberg and Phillips 2016), and institutional investor holdings (Backus, Conlon, and Sinkinson 2021) covering the universe of U.S. publicly listed corporations from 1995 to 2021. We perform counterfactual calculations to evaluate how the efficiency and the distributional impact of common ownership have evolved over this period, finding large negative consumer welfare effects.

Our model has two distinctive features. First, it leverages the Generalized Hedonic-Linear (GHL) demand system developed by Pellegrino (2019). This demand system is based on the assumption that there is a representative consumer with quadratic preferences over product characteristics. The inverse cross-price elasticity of demand between any two products is proportional to a metric of product similarity. Second, firms maximize a weighted sum of profits earned by their investors, following Rotemberg (1984), Lopez and Vives (2019), Backus, Conlon, and Sinkinson (2021), and Azar and Vives (2021).

**Key findings:** In 2021, we find that the deadweight loss of oligopoly amounts to about 13.9% of total surplus. Common ownership leads to an additional deadweight loss of 12.4% of total surplus. The welfare losses of common ownership fall entirely on consumers: in 2021, common ownership raises aggregate profits by $1.133 trillion (from $2.167 trillion to $3.300 trillion), but lowers consumer surplus by $2.399 trillion (from $7.402 trillion to $5.003 trillion). The deadweight loss attributable solely to common ownership increased about ninefold from 1.4% of total surplus in 1995 to 13.2% in 2021. Even under the most conservative governance assumptions (Azar and Rinaldi 2022 mitigation parameters), the deadweight loss remains around 3.5% of total surplus.

The remainder of the paper proceeds as follows. Section 2 develops the theoretical model. Section 3 describes the data and Section 4 reports the empirical results for the baseline model. Section 5 provides empirical results under a range of different corporate governance models and Section 6 discusses extensions. Section 7 concludes.

---

## 2. Theoretical Model

Building on Pellegrino (2019), we develop a general equilibrium model in which granular firms with overlapping ownership compete in a network game of Cournot oligopoly.

### 2.1 Generalized Hedonic-Linear (GHL) Demand

There is a representative agent who is a consumer, worker, and owner. Our economy has $n$ firms, indexed by $i \in \{1, 2, \dots, n\}$. Each firm produces a single differentiated product. The representative agent has hedonic demand (Lancaster 1966; Rosen 1974) and values each product as a bundle of its constituent characteristics.

Each product has two types of characteristics: $m$ common characteristics indexed by $\iota \in \{1, 2, \dots, m\}$ and one of $n$ idiosyncratic characteristics. The $m$-dimensional column vector $\mathbf{a}_i$ describes product $i$ where the scalar $a_{\iota i}$ is the number of units of common characteristic $\iota$ of product $i$. The vector $\mathbf{a}_i$ is of unit length:

$$\mathbf{a}_i = [a_{1i} \; a_{2i} \; \ldots \; a_{mi}]' \quad \text{such that} \quad \sum_{\iota=1}^{m} a_{\iota i}^2 = 1 \quad \forall \; i$$

We combine the product-specific vectors $\mathbf{a}_i$ in the $m \times n$ matrix $\mathbf{A}$.

The representative agent consumes $q_i$ units of the good produced by firm $i$. The total units $x_\iota$ of common characteristic $\iota$ consumed are $x_\iota = \sum_i a_{\iota i} q_i$, so that $\mathbf{x} = \mathbf{Aq}$.

The representative agent has utility quadratic in common and idiosyncratic product characteristics, and suffers a linear disutility for work hours $H$:

$$U(\mathbf{x}, \mathbf{q}, H) \; \overset{\text{def}}{=} \; \alpha \cdot \sum_{\iota=1}^m \left(b_\iota^x x_\iota - \frac{1}{2} x_\iota^2\right) + (1-\alpha) \sum_{i=1}^n \left(b_i^y y_i - \frac{1}{2} y_i^2\right) - H$$

where $\alpha \in [0,1]$ is the utility weight of common characteristics relative to idiosyncratic characteristics. If $\alpha = 0$, all firms are monopolists producing independent products; if $\alpha = 1$, the consumer's utility only depends on common characteristics.

The agent's budget constraint is $H + \Pi \geq \sum_{i=1}^n p_i q_i$, where $\Pi = \sum_i \pi_i$ is aggregate profits.

Labor is the numéraire. The consumer's demand maximizes the consumer surplus function:

$$\mathrm{CS}(\mathbf{q}) = \mathbf{q}'(\mathbf{b} - \mathbf{p}) - \frac{1}{2}\mathbf{q}'[\mathbf{I} + \alpha(\mathbf{A'A} - \mathbf{I})]\mathbf{q}$$

where $\mathbf{b} \overset{\text{def}}{=} \alpha \mathbf{A'b}^x + (1-\alpha)\mathbf{b}^y$.

The scalar $\mathbf{a}_i'\mathbf{a}_j$ is the **cosine similarity** between products $i$ and $j$ and ranges from 0 to 1. Products with higher cosine similarity are more substitutable. Define

$$\mathbf{\Sigma} \overset{\text{def}}{=} \alpha(\mathbf{A'A} - \mathbf{I})$$

with entries $\sigma_{ij}$. The diagonal elements $\sigma_{ii} = 0$; off-diagonal elements $\sigma_{ij} \in [0, \alpha]$. The resulting demand and inverse demand functions are:

$$\text{Aggregate demand:} \quad \mathbf{q} = (\mathbf{I} + \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{p})$$

$$\text{Inverse demand:} \quad \mathbf{p} = \mathbf{b} - (\mathbf{I} + \mathbf{\Sigma})\mathbf{q}$$

### 2.2 Labor Demand and Product Supply

Each firm $i$ produces output $q_i$ using labor $h_i$. The cost function is quadratic:

$$h_i(q_i) = f_i + c_i^0 q_i + \frac{\delta_i}{2} q_i^2 \quad \text{thus} \quad c_i = c_i^0 + \delta_i q_i$$

where $f_i$ and $c_i$ are firm $i$'s fixed and marginal costs. Fixed costs are sunk. The profits of firm $i$ are:

$$\pi_i(\mathbf{q}) = q_i b_i - q_i^2 - \sum_{j \neq i} \sigma_{ij} q_i q_j - h_i$$

### 2.3 Ownership and Firm Objective Function

There are $Z$ investment funds indexed by $z$. The income of fund $z$ is $V_z \overset{\text{def}}{=} \sum_{i=1}^n s_{iz} \pi_i$, where $s_{iz}$ is the proportion of shares of company $i$ owned by fund $z$, and $\sum_z s_{iz} = 1$.

Following Rotemberg (1984), firm $i$ maximizes $\phi_i$, the sum of all investment funds' value functions weighted by their ownership shares in firm $i$:

$$\phi_i \overset{\text{def}}{=} \sum_{z=1}^Z s_{iz} V_z = \sum_{j=1}^n \pi_j \sum_{z=1}^Z s_{iz} s_{jz}$$

Define the **common ownership weights** $\kappa_{ij}$ as:

$$\kappa_{ij} \overset{\text{def}}{=} \frac{\mathbf{s}_i'\mathbf{s}_j}{\mathbf{s}_i'\mathbf{s}_i}$$

This allows firm $i$'s objective function to be written as:

$$\phi_i \propto \pi_i + \sum_{j \neq i} \kappa_{ij} \pi_j$$

The weight $\kappa_{ij}$ is the weight—due to common ownership—that firm $i$'s objective assigns to the profits of other firms relative to its own. It corresponds to what Edgeworth (1881) termed the "coefficient of effective sympathy among firms." This objective nests standard Cournot competition ($\kappa_{ij} = 0$ for $i \neq j$) and monopoly ($\kappa_{ij} = 1$ for $i \neq j$) as limit cases. The $n \times n$ matrix $\mathbf{K}$ contains all bilateral common ownership weights with all $\kappa_{ii} = 1$.

Firms engage in Cournot competition. Firm $i$'s first order condition is:

$$\frac{\partial \phi_i}{\partial q_i} = \frac{\partial \pi_i}{\partial q_i} + \sum_{j \neq i} \kappa_{ij} \frac{\partial \pi_j}{\partial q_i} = 0$$

We focus on unilateral effects and do not consider coordinated effects of common ownership (e.g., increased collusion incentives).

### 2.4 Equilibrium, Market Structure, and Ownership Counterfactuals

Our baseline assumption is that firms compete in a **Cournot Common Ownership (CCO)** game in which the manager of each firm $i$ maximizes $\phi_i$. The CCO allocation $\mathbf{q}^\phi$ is:

$$\mathbf{q}^\phi = (2\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma} + \mathbf{K} \circ \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c}^0)$$

where $\mathbf{\Delta}$ is a diagonal matrix of marginal cost slopes $\delta_i$ and $\circ$ denotes the Hadamard (entry-by-entry) product.

This framework yields a **linear-quadratic network game** (Ballester, Calvo-Armengol, and Zenou 2006). The game admits the following three potential functions corresponding to different assumptions about firm behavior, ranked from least to most competitive:

$$\text{Aggregate Profit:} \quad \Pi(\mathbf{q}) = \mathbf{q}'(\mathbf{b} - \mathbf{c}^0) - \frac{1}{2}\mathbf{q}'(2\mathbf{I} + \mathbf{\Delta} + 2\mathbf{\Sigma})\mathbf{q} - F$$

$$\text{Cournot Potential:} \quad \Psi(\mathbf{q}) = \mathbf{q}'(\mathbf{b} - \mathbf{c}^0) - \frac{1}{2}\mathbf{q}'(2\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma})\mathbf{q} - F$$

$$\text{Total Surplus:} \quad W(\mathbf{q}) = \mathbf{q}'(\mathbf{b} - \mathbf{c}^0) - \frac{1}{2}\mathbf{q}'(\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma})\mathbf{q} - F$$

where $F \overset{\text{def}}{=} \sum_i f_i$.

**Definition (Monopoly).** The *Monopoly* allocation $\mathbf{q}^\Pi$ is the maximizer of $\Pi(\mathbf{q})$:

$$\mathbf{q}^\Pi = (2\mathbf{I} + \mathbf{\Delta} + 2\mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c}^0) \quad \text{if interior solution}$$

**Definition (Cournot).** The *Cournot* allocation $\mathbf{q}^\Psi$ is the maximizer of $\Psi(\mathbf{q})$ with all $\kappa_{ij} = 0$ for $i \neq j$:

$$\mathbf{q}^\Psi = (2\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c}^0) \quad \text{if interior solution}$$

**Definition (Perfect Competition).** The *Perfect Competition* allocation $\mathbf{q}^W$ is the maximizer of $W(\mathbf{q})$:

$$\mathbf{q}^W = (\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c}^0) \quad \text{if interior solution}$$

---

## 3. Data, Identification, and Validation

### 3.1 Cost Function

In the baseline model, the marginal cost slope $\delta_i = 0$ for all firms. Each firm thus faces an exogenous constant marginal cost $c_i = c_i^0$. This constant-returns-to-scale assumption follows Berry, Levinsohn, and Pakes (1995), Nevo (2001), and Goeree (2008). The assumption is relaxed in the decreasing-returns extension.

### 3.2 Firm Financials

We measure revenues ($p_i q_i$), variable costs ($\mathrm{TVC}_i$), and fixed costs ($f_i$) using Compustat data, corresponding to accounting revenues, Costs of Goods Sold (COGS), and Selling General and Administrative (SGA) costs, respectively. Following De Loecker, Eeckhout, and Unger (2020), we exclude firms with negative revenues, costs of goods sold, or gross margin.

**Table 1: Variable Definitions and Mapping to Data**

*Panel A: Observed Variables*

| Notation | Description | Measurement | Source |
|----------|-------------|-------------|--------|
| $p_i q_i$ | Revenues | Revenues | Compustat |
| $\mathrm{TVC}_i$ | Total Variable Costs | Costs of Goods Sold | Compustat |
| $f_i$ | Fixed Costs | Selling, General and Administrative Costs | Compustat |
| $\mathbf{a}_i'\mathbf{a}_j$ | Product Cosine Similarity | Word frequencies in 10-K Business Description | Hoberg and Phillips (2016) |
| $\mathbf{s}_i$ | Ownership | Number of shares divided by total shares outstanding | SEC 13(f) filings, Compustat |

*Panel B: Identified Variables and Parameters*

| Notation | Description | Identification |
|----------|-------------|----------------|
| $\delta_i$ | Marginal Cost Slope | $= 0$ in baseline model |
| $\alpha$ | Utility Weight on Common Characteristics | $= 0.12$ using Nevo (2001) as in Pellegrino (2019) |
| $q_i$ | Output | $\mathbf{q}$ such that $\uppi + \mathbf{f} = \mathrm{diag}(\mathbf{q})(\mathbf{I} + \frac{1}{2}\mathbf{\Delta} + \mathbf{K} \circ \mathbf{\Sigma})\mathbf{q}$ |
| $c_i^0$ | Marginal Cost Intercept | $= h_i/q_i - \frac{1}{2}\delta_i q_i$ |
| $(\mathbf{I} + \mathbf{\Sigma})$ | $\partial\mathbf{p}/\partial\mathbf{q}$ | $= (1-\alpha)\mathbf{I} + \alpha \mathbf{A'A}$ |
| $\mathbf{b}$ | Demand Intercept | $= (2\mathbf{I} + \mathbf{\Delta} + \mathbf{\Sigma} + \mathbf{K} \circ \mathbf{\Sigma})\mathbf{q} + \mathbf{c}^0$ |

### 3.3 Text-Based Product Similarity

Hoberg and Phillips (henceforth HP; 2016) compute time-varying product cosine similarities for firms in Compustat by analyzing the text of the firms' 10-K forms. HP construct a vocabulary of 61,146 words that firms use when describing their products, and that identify product characteristics. For each firm $i$, HP construct a vector of word occurrences $\mathbf{v}_i$ and normalize it to obtain the empirical counterpart of $\mathbf{a}_i$:

$$\mathbf{a}_i = \frac{\mathbf{v}_i}{\|\mathbf{v}_i\|}$$

All $\mathbf{a}_i$ vectors are dot-multiplied to obtain $\mathbf{A'A}$. To the extent that word frequencies correctly represent product characteristics, this matrix is the exact empirical counterpart to the matrix of cross-price effects in our theoretical model. It covers 97.8% of the CRSP-Compustat universe.

### 3.4 Ownership Data

We obtain the matrix of ownership shares $\mathbf{S}$ from two datasets of mutual fund holdings reported in SEC form 13(f) filings—mandatory for institutional investors with assets under management exceeding $100 million. Our data cover 1995 to 2021, combining a dataset from Backus, Conlon, and Sinkinson (2021) for 1999–2017 and Thomson Reuters 13(f) data for the remaining years.

We apply a statistical correction for unobserved investors to avoid a thick right tail of implausibly large $\kappa_{ij}$. Under the conservative assumption of zero overlap among unobserved investors, the numerator of $\kappa_{ij}$ is computed using only observed holdings. The denominator (the investor Herfindahl index) is corrected upward using:

$$\mathrm{IHHI}_i^* = \left[1 + \left(\frac{1 - S_{i(\mathcal{O})}}{S_{i(\mathcal{O})}}\right)^2\right] \cdot \widehat{\mathrm{IHHI}}_i$$

This construction implies that our estimates of the welfare impact of common ownership are, by construction, conservative.

### 3.5 Identification

The remaining unobserved variables are identified given $\alpha$ and $\mathbf{\Delta}$.

**Assumption 1.** There are as many common characteristics as words: $\mathbf{v}_i$ and $\mathbf{a}_i$ are vectors in $\mathbb{R}^m$.

**Assumption 2.** For all $i$, the vectors $\mathbf{v}_i$ and $\mathbf{a}_i$ are collinear up to a permutation.

To identify $\mathbf{q}$, we write the vector of firm profits $\uppi$ and fixed costs $\mathbf{f}$ as:

$$\uppi + \mathbf{f} = \mathrm{diag}(\mathbf{q})\left(\mathbf{I} + \frac{1}{2}\mathbf{\Delta} + \mathbf{K} \circ \mathbf{\Sigma}\right)\mathbf{q}$$

and solve for $\mathbf{q}$ numerically. The inverse cross-price demand elasticity is:

$$\epsilon_{ij} = \frac{\partial \log p_i}{\partial \log q_j} = -\frac{q_j}{p_i} \sigma_{ij}$$

The parameter $\alpha$ is identified from:

$$\alpha = -\frac{\epsilon_{ij} p_i q_j + \epsilon_{ji} p_j q_i}{2 \cos_{ij}^{\mathrm{HP}} \sqrt{p_i q_i - \mathrm{TVC}_i} \sqrt{p_j q_j - \mathrm{TVC}_j}}$$

Following Pellegrino (2019), we use the inverse cross-price elasticity between Kellogg's and Quaker Oats from Nevo (2001) to obtain $\alpha = 0.12$.

### 3.6 Validation

**Clusters of the Product Similarity Network.** Pellegrino (2019) shows a near-perfect overlap between the community structure of HP's network and GICS industry classifications, without the graph targeting these classifications.

**Self-Reported Rivalries.** HP (2016) show that their industry classification built from product similarity data (TNIC) strongly outperforms traditional industry classifications (NAICS, SIC) in predicting product market rivalries.

**Demand Estimates.** Pellegrino (2019) compares GHL elasticities to landmark industrial organization studies on automobiles (Berry, Levinsohn, and Pakes 1995), ready-to-eat cereals (Nevo 2001), and computers (Goeree 2008). The signs of GHL estimates are identical to corresponding IO estimates for every firm pair, and the magnitudes are similar despite $\alpha = 0.12$ being the only free parameter for the entire economy across all years. The results are shown in Table 2 below.

**Table 2: Microeconometric Estimates vs. GHL (Pellegrino 2019)**

| Market | Firm $i$ | Firm $j$ | Micro Estimate | GHL |
|--------|----------|----------|----------------|-----|
| Auto | Ford | Ford | −4.320 | −5.197 |
| Auto | Ford | General Motors | 0.034 | 0.056 |
| Auto | Ford | Toyota | 0.007 | 0.017 |
| Auto | General Motors | Ford | 0.065 | 0.052 |
| Auto | General Motors | General Motors | −6.433 | −4.685 |
| Auto | General Motors | Toyota | 0.008 | 0.005 |
| Auto | Toyota | Ford | 0.018 | 0.025 |
| Auto | Toyota | General Motors | 0.008 | 0.008 |
| Auto | Toyota | Toyota | −3.085 | −4.851 |
| Cereals | Kellogg's | Kellogg's | −3.231 | −1.770 |
| Cereals | Kellogg's | Quaker Oats | 0.033 | 0.023 |
| Cereals | Quaker Oats | Kellogg's | 0.046 | 0.031 |
| Cereals | Quaker Oats | Quaker Oats | −3.031 | −1.941 |
| Computers | Apple | Apple | −11.979 | −8.945 |
| Computers | Apple | Dell | 0.018 | 0.025 |
| Computers | Dell | Apple | 0.027 | 0.047 |
| Computers | Dell | Dell | −5.570 | −5.110 |

---

## 4. Empirical Results

### 4.1 Product Similarity and Common Ownership

**[Figure B.1: Network Visualization]** Two-dimensional representations of the product similarity network (left panel) and the ownership network (right panel) for all publicly listed firms in 2008. Firm pairs closer in product market and ownership space have thicker links. Networks were projected from approximately 61,000 and 2,800 dimensions respectively using the OpenOrd (Martin et al. 2011) and Fruchterman-Reingold (1991) algorithms. The product similarity network displays a pronounced community structure with firms clustering in industry groups. In contrast, the ownership network has a hub-and-spoke structure, with a large proportion of firms sharing significant overlap.

**[Figure B.2: Network Evolution — Product Similarity and Ownership]** Two-dimensional representations of the product similarity and ownership networks in 1995 (top panels) and 2021 (bottom panels), with firm positions held fixed for comparability. The ownership network is dramatically more connected in 2021 than in 1995. The product similarity network is somewhat more connected in 1995, consistent with firms becoming more differentiated over time.

**[Figure B.3: Product Similarity and Profit Weights (2021)]** A histogram of the joint distribution of product similarity $\mathbf{a}_i \cdot \mathbf{a}_j$ and profit weights $\kappa_{ij}$ for all firm pairs in 2021. A large proportion of pairs has little similarity and little ownership overlap. The correlation between the two variables is only 0.0264, confirming that common ownership is not systematically more pronounced for product-market competitors.

**[Figure B.4: Combined Network Visualization (2021)]** A two-dimensional overlay of both networks: the product similarity network (blue) and the ownership network (pink). The pink ownership network has a single large cluster; the blue product similarity network has multiple clusters that do not overlap in any particular way with the ownership network.

The average value of $\mathbf{a}_i'\mathbf{a}_j$ changes little, from 0.0171 in 1995 to 0.0174 in 2021. In contrast, the average $\kappa_{ij}$ rises almost sevenfold from 0.0021 in 1995 to 0.0146 in 2021.

### 4.2 Welfare, Consumer Surplus, and Profit Estimates

These baseline estimates assume investors exert influence proportional to ownership shares (Rotemberg proportional weights).

**Table A.1: Welfare Estimates (2021)**

| Welfare Statistic | Variable | (1) Common Ownership $\mathbf{q}^\phi$ | (2) Cournot-Nash $\mathbf{q}^\Psi$ | (3) Perfect Competition $\mathbf{q}^W$ | (4) Monopoly $\mathbf{q}^\Pi$ |
|---|---|---|---|---|---|
| Total Surplus (US$ trillions) | $W(\mathbf{q})$ | 8.303 | 9.570 | 11.116 | 7.629 |
| Aggregate Profits (US$ trillions) | $\Pi(\mathbf{q})$ | 3.300 | 2.167 | 0.000 | 4.141 |
| Consumer Surplus (US$ trillions) | $\mathrm{CS}(\mathbf{q})$ | 5.003 | 7.402 | 11.116 | 3.488 |
| Total Surplus / Perfect Competition | $W(\mathbf{q})/W(\mathbf{q}^W)$ | 0.747 | 0.861 | 1.000 | 0.686 |
| Aggregate Profit / Total Surplus | $\Pi(\mathbf{q})/W(\mathbf{q})$ | 0.397 | 0.226 | 0.000 | 0.543 |
| Consumer Surplus / Total Surplus | $\mathrm{CS}(\mathbf{q})/W(\mathbf{q})$ | 0.603 | 0.774 | 1.000 | 0.457 |

The welfare costs of common ownership are substantial but not as large as the welfare costs of oligopoly. The deadweight loss of oligopoly amounts to 13.9% of total surplus. On top of that, common ownership leads to an additional deadweight loss of 11.4% of total surplus under perfect competition.

The welfare losses of common ownership fall entirely on consumers. Common ownership lowers consumer surplus by $2.399 trillion (from $7.402 trillion to $5.003 trillion) and raises aggregate profits by $1.133 trillion (from $2.167 trillion to $3.300 trillion), generating a net deadweight loss of $1.267 trillion.

### 4.3 Time Trends in Welfare, Consumer Surplus, and Profits

**[Figure B.5: Total Surplus of U.S. Public Firms]** Annual aggregate consumer surplus and profits between 1995 and 2021 for the CCO equilibrium, with profits as a share of total surplus on the right axis. Total surplus produced by U.S. public corporations increased from $5.632 trillion to $8.303 trillion between 1995 and 2021. Profits increased from $1.003 trillion to $3.300 trillion; consumer surplus increased from $4.629 trillion to $5.003 trillion. The profit share increased from 17.8% to 39.7%.

**[Figure B.6: Profit Share of Total Surplus]** Profit share under standard Cournot (light green) and Cournot with common ownership (dark green) from 1995 to 2021. Under standard Cournot, the profit share increases by roughly 7 percentage points (15.8% to 22.6%). Under common ownership, the increase is more than twice as large—over 20 percentage points (17.8% to 39.7%).

**[Figure B.7: Deadweight Loss]** Estimated deadweight loss (DWL) of oligopoly (dark green) and of oligopoly plus common ownership (light green) from 1995 to 2021. DWL increases from 8.0% and 9.3% in 1995 to 13.9% and 25.3% in 2021.

**[Figure B.8: Common Ownership — Deadweight Loss and Distributional Effects]** *Left panel:* DWL attributable solely to common ownership (difference between DWL with and without common ownership). Increases from 1.4% of total surplus in 1995 to 13.2% in 2021—a ninefold increase. *Right panel:* Effect of common ownership on profits and consumer surplus as percentage differences between Cournot and CCO allocations from 1995 to 2021. Common ownership raised corporate profits by 11.4% in 1995 and 52.2% in 2021; it lowered consumer surplus by 3.8% in 1995 and 32.4% in 2021.

---

## 5. Corporate Governance under Common Ownership

### 5.1 Superproportional Influence of Large Investors

The baseline model assumes proportional influence. However, larger investors may exert influence exceeding the size of their stake (Azar 2021; Gilje, Gormley, and Levit 2020). We compute influence-adjusted common ownership weights:

$$\tilde{\kappa}_{ij} \overset{\text{def}}{=} \frac{\sum_{z=1}^Z s_{iz} \gamma_{iz} s_{jz}}{\sum_{z=1}^Z s_{iz} \gamma_{iz} s_{iz}}$$

Following Gilje, Gormley, and Levit (2020) and Backus, Conlon, and Sinkinson (2021), we approximate the influence function using a square root: $\gamma_{iz} \overset{\text{def}}{=} \sqrt{s_{iz}}$.

### 5.2 Blockholder Thresholds

Blockholders are investors holding 5% or more of a company's stock (the SEC disclosure threshold). Under this assumption, firm $i$ internalizes the impact of its production decisions on investor $z$'s portfolio profits only if investor $z$ is a blockholder of firm $i$. The blockholder-adjusted common ownership weights are:

$$\tilde{\kappa}_{ij} \overset{\text{def}}{=} \frac{\sum_{z=1}^Z s_{iz} B_{iz} s_{jz}}{\sum_{z=1}^Z s_{iz} s_{jz}} \quad \text{for } i \neq j$$

where $B_{iz} = 1$ if and only if $s_{iz} > 5\%$.

### 5.3 Rational Investor Inattention

Gilje, Gormley, and Levit (henceforth GGL; 2020) highlight the importance of investor inattention. GGL propose a measure of common ownership incorporating attention weights $g_{iz} \in [0,1]$, estimated non-parametrically as the probability of investor $z$ deviating from Institutional Shareholders Service (ISS) voting recommendations. The inattention-modified sympathy weight is:

$$\bar{\kappa}_{ij} \overset{\text{def}}{=} \frac{1}{0.07} \cdot \frac{\mathrm{GGL}_{ij}^{\mathrm{fitted}}}{\mathrm{IHHI}_i} = \frac{1}{0.07} \cdot \frac{\mathrm{GGL}_{ij}^{\mathrm{fitted}}}{\mathrm{GGL}_{ij}^{\mathrm{full}}} \cdot \kappa_{ij}$$

where the factor 1/0.07 normalizes by the full-attention disagreement probability. By construction, $0 \leq \bar{\kappa}_{ij} \leq \kappa_{ij}$, so investor inattention dampens the product market effects of common ownership.

### 5.4 Governance Frictions and Managerial Entrenchment

Azar and Rinaldi (henceforth AR; 2022) develop a flexible objective function allowing for partial managerial entrenchment:

$$\phi \propto \pi + \tau_i \sum_{j \neq i} \kappa_{ij} \pi_j$$

The mitigation factor is:

$$\tau_i = \frac{\gamma \psi \mathrm{IHHI}_i}{1 + \gamma \psi \mathrm{IHHI}_i}$$

where $\gamma$ is the cost of shareholder dissent and $\psi$ the responsiveness of shareholders to managerial behavior. We consider: (i) a uniform mitigation factor $\tau = 0.29$; and (ii) the best-fitting structural AR specification with $\theta_0 = \log(\gamma \psi) = 2.6844$, which also yields a median mitigation factor of 0.29.

### 5.5 Empirical Results

**[Figure B.9: Common Ownership DWL — Alternative Governance Models]** Evolution of the deadweight loss of common ownership under proportional, superproportional, and blockholder influence models, the GGL inattention model, and the AR partial internalization models from 1995 to 2021. Key findings:
- Superproportional influence yields deadweight loss similar to the proportional baseline.
- Blockholder common ownership has little effect until ~2013, then rises rapidly to ~9% by 2021, driven by BlackRock and Vanguard crossing the 5% threshold for many firms.
- GGL inattention model yields ~10% deadweight loss in 2021.
- AR partial internalization models (uniform or firm-specific) yield ~3.5% deadweight loss in 2021.

**[Figure B.10: Distributional Effects — Alternative Governance Models]** *Left panel:* effect of common ownership on profits; *right panel:* effect on consumer surplus, under different governance models. Even with blockholder thresholds, common ownership raises firm profits by almost 30% and lowers consumer surplus by almost 24% in 2021. Under GGL and AR governance, the distributional consequences are more muted but still substantial.

---

## 6. Extensions and Discussion

### 6.1 Private and Foreign Firms

We extend the model to include a continuum of atomistic firms representing private and foreign firms. For each of 30 macro-sectors, a representative competitive firm prices at marginal cost. The equilibrium quantity vector becomes:

$$\mathbf{q}^\phi = (\mathbf{I} + \mathbf{G} + \mathbf{\Delta} + \mathbf{\Sigma} + \mathbf{K} \circ \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c}^0)$$

where $\mathbf{G}$ is a diagonal matrix with 1 for oligopolistic firms and 0 for the competitive representative firm.

When accounting for private and foreign firms, the estimated deadweight loss of common ownership is about one-third that of the baseline. This is because (i) the share of surplus generated by private and foreign firms increases as the number of public firms declines; (ii) private and foreign firms are assumed independently owned; (iii) the supply reduction by commonly-owned public firms induces private and foreign firms to expand output under strategic substitutability.

### 6.2 Multi-product Firms

We augment the model to allow $n$ firms to produce $\hat{n} \geq n$ products. The augmented ownership matrix $\hat{\mathbf{K}}$ has entry $\hat{\kappa}_{ij} = 1$ if products $i$ and $j$ are produced by the same firm, and otherwise equals the bilateral $\kappa$ for the producing firms. The equilibrium is:

$$\mathbf{q}^\phi = (2\mathbf{I} + \mathbf{\Delta} + \hat{\mathbf{\Sigma}} + \hat{\mathbf{K}} \circ \hat{\mathbf{\Sigma}})^{-1}(\mathbf{b} - \mathbf{c}^0)$$

The estimated deadweight loss with multi-product firms is slightly larger than in the baseline, because within-firm internalization across product lines amplifies the anticompetitive effect.

### 6.3 Complements

The GHL demand system restricts products to be substitutes or independent. To investigate sensitivity, for each year we randomly flip the sign of 5% of product-pair similarity entries in $\Sigma$, creating artificial complements. The deadweight loss is slightly smaller than baseline estimates. Complementarities alleviate the deadweight loss of common ownership because common ownership of firms with complementary products leads them to produce more than under standard Cournot.

### 6.4 Geography and Tradable Industries

Although we cannot account for geographic sub-markets within the U.S., we show that results are largely unchanged when restricting to firms in tradable industries only, where geography is less critical.

### 6.5 Bertrand Oligopoly

All analyses can be replicated under Bertrand competition. The Bertrand Common Ownership equilibrium quantity vector (assuming flat marginal costs, $\mathbf{\Delta} = 0$) is:

$$\mathbf{q}^{\mathrm{B}} = [\mathbf{I} + \mathbb{D}^{-1} + \mathbf{\Sigma} + \mathbb{D}^{-1}(\mathbf{K} \circ \mathbb{O})(\mathbf{I} + \mathbf{\Sigma})]^{-1}[\mathbf{I} + \mathbb{D}^{-1}(\mathbf{K} \circ \mathbb{O})](\mathbf{b} - \mathbf{c})$$

where $\mathbb{D}$ and $\mathbb{O}$ are the diagonal and off-diagonal elements of $(\mathbf{I} + \mathbf{\Sigma})^{-1}$. Because Bertrand competition is more intense than Cournot, the deadweight loss from oligopoly is smaller under Bertrand, but the incremental anticompetitive effect of common ownership is more pronounced. Our Cournot estimates are therefore conservative.

### 6.6 Limitations

Our analysis assumes quantity-setting Cournot oligopoly and abstracts from other channels through which common ownership may affect welfare: labor market power (Azar and Vives 2021), collusion incentives (Pawliczek, Rinaldi, and Shue 2019; Shekita 2020), productivity and cost efficiency (Anton et al. 2023), innovation (Lopez and Vives 2019; Anton et al. 2024), entry (Newham, Serafeim, and Tognato 2019; Xie 2020), and product differentiation choices.

### 6.7 Empirical Results

**[Figure B.11: Common Ownership DWL — Extensions]** Evolution of the deadweight loss of common ownership under all model extensions. All specifications show large and growing welfare costs of common ownership. The estimated deadweight losses in 1995 range between 0.5% and 1.5%; they rise to between 5.3% and 15.1% by 2021. The only extension yielding markedly different (though time-trend-consistent) results is the private and foreign firms extension. Even the most conservative estimates combining AR governance frictions and private/foreign firms suggest a deadweight loss of approximately 1.5% of total surplus.

---

## 7. Conclusions

We provide the first quantification of the welfare and distributional effects of common ownership at the macroeconomic level. Our general equilibrium model of oligopoly features firms connected through two large networks of product similarity and ownership overlap. Baseline estimates indicate that the rise of common ownership has led to considerable and growing deadweight losses since 1995, reaching 13.2% of total surplus in 2021. The welfare costs fall entirely on consumers, while producers benefit. These conclusions hold under alternative corporate governance assumptions and various model extensions.

The economically large impact of common ownership predicted by our model suggests that its continuing increase carries important implications for antitrust policy and financial regulation.

---

## Appendix

### A.1 Welfare Estimates (1995)

**Table A.2: Welfare Estimates (1995)**

| Welfare Statistic | Variable | (1) Common Ownership | (2) Cournot-Nash | (3) Perfect Competition | (4) Monopoly |
|---|---|---|---|---|---|
| Total Surplus (US$ trillions) | $W(\mathbf{q})$ | 5.632 | 5.712 | 6.206 | 4.437 |
| Aggregate Profits (US$ trillions) | $\Pi(\mathbf{q})$ | 1.003 | 0.900 | 0.000 | 2.668 |
| Consumer Surplus (US$ trillions) | $\mathrm{CS}(\mathbf{q})$ | 4.629 | 4.811 | 6.206 | 1.769 |
| Total Surplus / Perfect Competition | 0.907 | 0.920 | 1.000 | 0.715 |
| Aggregate Profit / Total Surplus | 0.178 | 0.158 | 0.000 | 0.601 |
| Consumer Surplus / Total Surplus | 0.822 | 0.842 | 1.000 | 0.399 |

### A.2 Firm-Level Profit Effects

**Table A.3: Top and Bottom 10 Companies by Profit Difference between CCO and Cournot (2021)**

*Top 10 (largest profit increase due to common ownership):*

| Company | CCO Profits ($M) | Cournot Profits ($M) | Difference ($M) | % Diff. |
|---------|-----------------|---------------------|-----------------|---------|
| Microsoft | $80,816 | $67,889 | +$12,927 | +19.0% |
| Walmart | $36,037 | $23,270 | +$12,767 | +54.9% |
| Alphabet | $91,144 | $82,064 | +$9,080 | +11.1% |
| AT&T | $51,469 | $44,108 | +$7,361 | +16.7% |
| Dell | $10,791 | $3,579 | +$7,212 | +201.5% |
| Verizon | $47,948 | $40,737 | +$7,211 | +17.7% |
| Oracle | $18,564 | $12,033 | +$6,531 | +54.3% |
| Amazon | $47,850 | $41,702 | +$6,148 | +14.7% |
| Home Depot | $23,051 | $16,930 | +$6,121 | +36.2% |
| CVS | $17,944 | $11,851 | +$6,094 | +51.4% |

*Bottom 10 (largest profit decrease due to common ownership):*

| Company | CCO Profits ($M) | Cournot Profits ($M) | Difference ($M) | % Diff. |
|---------|-----------------|---------------------|-----------------|---------|
| Ulta Beauty | $569 | $1,458 | −$889 | −61.0% |
| Generac Holdings | $829 | $1,675 | −$846 | −50.5% |
| Etsy | $577 | $1,320 | −$743 | −56.3% |
| PSEG | $360 | $1,096 | −$736 | −67.1% |
| Palo Alto Networks | $2 | $719 | −$717 | −99.8% |
| Mastec | $843 | $1,542 | −$699 | −45.4% |
| Liberty Broadband | $264 | $915 | −$651 | −71.2% |
| Five9 | $2 | $497 | −$496 | −99.7% |
| Ciena | $611 | $1,059 | −$448 | −42.3% |
| Solaredge | $248 | $638 | −$390 | −61.2% |

---

## Online Appendix

### B.1 Decreasing Returns to Scale

We relax the constant marginal cost assumption. Following Pellegrino (2019), the marginal cost slope is bounded using a set identification result:

$$\delta_{\mathcal{S}(i)} \leq \min_{i' \in \mathcal{S}(i) \cap \mathcal{F}} \frac{2 \times \mathrm{TVC}_i}{p_i q_i - 2 \times \mathrm{TVC}_i}$$

where $\mathcal{S}(i)$ is the set of firms in the sector of firm $i$ and $\mathcal{F}$ is the set of firms whose revenues are at least twice total variable costs.

**[Figure B.12: Implied Markup Distribution]** Distribution of firm markups estimated by the model with decreasing returns to scale under common ownership in 1995 and 2021.

**[Figure B.13: Evolution of Markup Percentiles]** 10th, 25th, 50th, 75th, and 90th percentile of firm markups from 1995 to 2021 under decreasing returns to scale.

**[Figure B.14: Comparison of Markups with Pellegrino (2019)]** Distribution of markups in 2021: our model vs. Pellegrino (2019).

**[Figure B.15: Comparison of Markups with De Loecker, Eeckhout, and Unger (2020)]** Distribution of markups in 2016 (most recent year in their sample): our model vs. DEU.

**[Figure B.16: Comparison of Markup Evolution with De Loecker, Eeckhout, and Unger (2020)]** Revenue-weighted average markup: our model vs. DEU, using the most recent available year for each firm.

**[Figure B.17: Cross-sectional Comparison of Markups with De Loecker, Eeckhout, and Unger (2020)]** Cross-sectional plot of markups from our model vs. DEU in 2016.

### B.2 Consumption Baskets of Corporate Managers

We allow corporate managers to consume some goods from the basket of the representative consumer. The manager's utility is:

$$U^i \propto \rho \mathrm{CS} + \phi_i$$

where $\rho \in [0,1]$ controls how much the manager's consumption basket loads on non-luxury goods. If $\rho = 0$, we recover the baseline. If $\rho > 0$, managers partially internalize consumer surplus when setting quantities. We report results for $\rho = 0.25$.

### B.3 Bertrand Oligopoly with Common Ownership

The Bertrand Common Ownership equilibrium is derived under flat marginal costs ($\mathbf{\Delta} = 0$). Writing profits as:

$$\uppi = \mathrm{diag}(\mathbf{p} - \mathbf{c})\left[\mathbb{D}(\mathbf{b} - \mathbf{p}) + \mathbb{O}(\mathbf{b} - \bar{\mathbf{p}})\right]$$

where $\mathbb{D}$ and $\mathbb{O}$ are the diagonal and off-diagonal elements of $(\mathbf{I} + \mathbf{\Sigma})^{-1}$. The first order condition yields the Bertrand equilibrium quantity vector:

$$\mathbf{q}^{\mathrm{B}} = [\mathbf{I} + \mathbb{D}^{-1} + \mathbf{\Sigma} + \mathbb{D}^{-1}(\mathbf{K} \circ \mathbb{O})(\mathbf{I} + \mathbf{\Sigma})]^{-1}[\mathbf{I} + \mathbb{D}^{-1}(\mathbf{K} \circ \mathbb{O})](\mathbf{b} - \mathbf{c})$$

### B.4 Product Market Centrality

Following Pellegrino (2019), the product market centrality $\chi_i$ of firm $i$ is defined by:

$$\chi_i: \quad q_i = \frac{1 - \chi_i}{2} \cdot (b_i - c_i)$$

where $(1 - \chi_i)$ is a generalized eigenvector summarizing the matrix $(2\mathbf{I} + \mathbf{\Sigma} + \mathbf{K} \circ \mathbf{\Sigma})^{-1}$. Centrality ranges from 0 (peripheral, monopoly markup) to 1 (central, perfectly competitive). The aggregate profit share is an average measure of centrality for the combination of both networks.

**[Figure B.18: Product Market Centrality]** Distribution of product market centralities under Cournot competition with and without common ownership in 1995 and 2021.
