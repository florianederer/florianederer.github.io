# Mergers and Acquisitions under Common Ownership

**Miguel Antón** (IESE Business School)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Mireia Giné** (IESE Business School, ECGI, and WRDS)
**Bruno Pellegrino** (University of Maryland and CESifo)

*AEA Papers & Proceedings*, Vol. 113, pp. 294–298, May 2023

---

## Abstract

We provide new facts about the cross-section and evolution of mergers and acquisitions for U.S. public firms. Using a general equilibrium model with a hedonic demand system and data on institutional ownership, we document that mergers are increasingly concentrated among firm pairs with a high degree of product market interaction and a moderate-to-high degree of common ownership. We estimate how much mergers have raised aggregate corporate profits and reduced consumer surplus and quantify how the anti-competitive effects of mergers are affected by common ownership and shareholder value maximization motives.

---

## Theory

The paper employs the general equilibrium models of Pellegrino (2019) and Ederer and Pellegrino (2022) in which $n$ single-product oligopolistic firms with overlapping ownership produce differentiated products and compete in a network game of Cournot oligopoly. A representative agent with quadratic utility over product characteristics consumes all goods produced in the economy, supplies labor, and receives income from owning shares of the firms. This yields the following linear inverse demand system:

$$\mathbf{p} = \mathbf{b} - (\mathbf{I} + \mathbf{\Sigma})\mathbf{q}$$

where $\mathbf{p}$ and $\mathbf{q}$ are the price and quantity vectors, $\mathbf{b}$ is the vector of demand intercepts (interpretable as measures of product quality), and $\mathbf{\Sigma}$ is the $n \times n$ matrix of price-quantity derivatives for all pairs of products.

Under the assumption that firms maximize a share-weighted sum of the profits earned by their shareholders, each firm $i$'s objective function is:

$$\phi_i \propto \pi_i + \sum_{j \neq i} \kappa_{ij} \pi_j$$

where $\kappa_{ij}$ is the weight that firm $i$ attaches to firm $j$'s profits:

$$\kappa_{ij} \equiv \frac{\sum_z s_{iz} s_{jz}}{\sum_z s_{iz} s_{iz}}$$

and $s_{iz}$ is the ownership share of firm $i$ accruing to shareholder $z$. The $n \times n$ matrix $\mathbf{K}$ contains the bilateral common ownership weights $\kappa_{ij}$ for all firms in the economy.

The Cournot-Nash equilibrium quantity allocation under common ownership $\mathbf{q}^{\Xi}$ is:

$$\mathbf{q}^{\Xi} = (2\mathbf{I} + \mathbf{\Sigma} + \mathbf{K} \circ \mathbf{\Sigma})^{-1}(\mathbf{b} - \mathbf{c})$$

where $\circ$ denotes the Hadamard (entry-by-entry) product and $\mathbf{c}$ is the vector of marginal costs. Under standard Cournot competition, $\kappa_{ij} = 0$ for all $i \neq j$.

The diversion ratio $\mathrm{DR}_{ij}$, measuring the change in quantity demanded of product $i$ for a price change in product $j$ that yields a unit decrease in the quantity demanded of $j$, is:

$$\mathrm{DR}_{ij} \equiv \frac{\partial q_i}{\partial p_j}\left(\frac{\partial q_j}{\partial p_j}\right)^{-1} = \frac{(\mathbf{I} + \mathbf{\Sigma})^{-1}_{ij}}{(\mathbf{I} + \mathbf{\Sigma})^{-1}_{jj}}$$

---

## Data

**Firm financials.** Revenues, variable costs, and fixed costs come from Compustat, corresponding to accounting revenues, cost of goods sold, and selling, general and administrative costs, respectively.

**Product similarity.** Hoberg and Phillips (2016) provide a time-varying estimate of the matrix of product-based cosine similarities between firms, constructed by text-mining the business description section of 10-K forms using a vocabulary of 61,146 words. Pellegrino (2019) shows how to identify the substitutability matrix $\mathbf{\Sigma}$ from the Hoberg-Phillips cosine similarity data.

**Ownership data.** The matrix of common ownership profit weights $\mathbf{K}$ is calculated using the methodology of Ederer and Pellegrino (2022), combining 13(f) data from Thomson Reuters (WRDS) and from Backus, Conlon, and Sinkinson (2021) who directly parsed SEC 13(f) forms.

**Merger data.** Announced mergers of public firms come from the database constructed by Ewens and Rhodes-Kropf (2015) and Phillips and Zhdanov (2013), covering publicly-traded companies up to 2016.

---

## Results

### Features of Mergers

For every firm pair $ij$, the paper computes the average common ownership weight $\kappa_{ij}$ and the average diversion ratio $\mathrm{DR}_{ij}$, then constructs within-year decile bins on both dimensions and measures what proportion of mergers falls into each bin.

Mergers are heavily concentrated among firm pairs with high diversion ratios: 65.2% of all mergers of public firms involved pairs in the highest decile of diversion ratios. Mergers were also particularly frequent among firms with high common ownership: 26.3% of all mergers fell in the highest decile of common ownership.

This concentration intensified over time. In 1996–2005, 64.3% of mergers were among firm pairs in the highest decile of diversion ratios, rising to 66.7% in 2006–2015. The share of mergers in the two highest deciles of common ownership rose from 35.4% in 1996–2005 to 39.0% in 2006–2015.

### Distributional Effects of Mergers

The paper simulates all mergers announced in the following year and estimates the counterfactual change in firm profits, consumer surplus, and total surplus under two assumptions: standard Cournot competition and Cournot competition with common ownership.

**Effect on profits.** Under standard Cournot competition, mergers raise total firm profits by between 0.17% and 0.58% per year. The profit-increasing effect is substantially smaller when firms internalize common ownership concerns: mergers raise aggregate profits by only 0.06% to 0.51%. In the later part of the sample, the profit increase from mergers under common ownership is only about 40% of the effect under standard Cournot. This is because mergers increasingly occur between firms that share a large proportion of common owners and thus already partially internalize each other's profit impact before the merger; common ownership acts like a partial merger, dampening the incremental profit impact of formal mergers.

**Effect on consumer surplus.** Mergers reduce consumer surplus by 0.06% to 0.18% per year under standard Cournot and by 0.05% to 0.16% under Cournot with common ownership. The dampening effect of common ownership on consumer surplus is much less pronounced than for profits: the reduction in consumer surplus under common ownership is essentially the same as under standard Cournot in 1996 and roughly 70% as large in 2015.

**Effect on total surplus.** Although mergers substantially increase profits, the combined impact on total surplus is negative because of the adverse effect on consumer surplus, which constitutes a larger share of total surplus. Mergers reduce total surplus by up to 0.07% under Cournot and 0.06% under Cournot with common ownership. The cumulative dollar value for 2006–2015 amounts to $64 billion and $44 billion under the two scenarios.

---

## Conclusion

Mergers of U.S. public corporations have become increasingly concentrated among firm pairs with a high degree of product market interaction and a moderate-to-high degree of common ownership. Under shareholder value maximization, rising common ownership may have mitigated some — but far from all — of the anti-competitive effects of mergers on consumer surplus. Even in the presence of high and rising common ownership, the estimated welfare loss resulting from mergers remains substantial.
