# The Great Startup Sellout and the Rise of Oligopoly

**Florian Ederer** (Yale University and NBER)
**Bruno Pellegrino** (University of Maryland and CESifo)

*AEA Papers & Proceedings*, Vol. 113, pp. 274–278, May 2023

---

## Abstract

We document a secular shift from IPOs to acquisitions of venture capital-backed startups and show that this trend is accompanied by an increase in the opportunity cost of going public over the last quarter century. Dominant companies that are disproportionately active in the corporate control market for startups have become more insulated from the pressures of product market competition over the same period. These facts are consistent with the hypothesis that startup acquisitions have contributed to rising oligopoly power.

---

## Theory

The paper employs the general equilibrium model of Pellegrino (2019) in which $n$ single-product granular firms produce differentiated products and compete in a network game of Cournot oligopoly. Each firm $i$ produces a differentiated good consisting of a $k$-dimensional vector of common characteristics $\mathbf{a}_i$ and a single unit of an idiosyncratic characteristic. A representative agent with quadratic utility over product characteristics yields the following linear inverse demand system:

$$\mathbf{p} = \mathbf{b} - (\mathbf{I} + \mathbf{\Sigma})\mathbf{q}$$

where $\mathbf{p}$ and $\mathbf{q}$ are price and quantity vectors, $\mathbf{b}$ is the vector of demand intercepts (interpretable as product quality), and $\mathbf{\Sigma}$ is the $n \times n$ matrix of price-quantity derivatives:

$$\mathbf{\Sigma} \equiv \alpha(\mathbf{A}'\mathbf{A} - \mathbf{I})$$

where $\alpha$ is the weight the representative agent attaches to common product characteristics and $\mathbf{A}'\mathbf{A}$ contains the dot products (cosine similarities) $\mathbf{a}_i'\mathbf{a}_j$ of the common characteristics of all firm pairs.

The Cournot equilibrium output of firm $i$ is:

$$q_i^{\Phi} = \frac{1 - \chi_i}{2}(b_i - c_i)$$

where $b_i$ is the firm's demand intercept and $\chi_i$ is its **product market centrality**, derived from the economy's matrix of product market similarities.

Product market centrality determines how close firm $i$'s actual equilibrium markup $\mu_i$ is to the competitive markup (equal to 1) versus the monopolistic markup $\bar{\mu}_i$:

$$\mu_i = \chi_i + (1 - \chi_i)\bar{\mu}_i$$

When $\chi_i$ is close to 1, the firm is very central — it has many rivals supplying similar products and behaves like an atomistic price-taker. When $\chi_i$ is close to 0, the firm is at the periphery of the product market rivalry network and sets output like a monopolist. A lower $\chi_i$ insulates the firm from competitive pressures.

The minimum productivity level for a potential entrant to survive (making weakly positive economic profits, given the output of every other firm) is $b_i - c_i - 2q_i^{\Phi}$. The **entrant productivity premium** (EPP) measures the gap between a firm's actual productivity and this minimum threshold as a fraction of the threshold:

$$\mathrm{EPP}_i = \frac{2q_i^{\Phi}}{b_i - c_i - 2q_i^{\Phi}}$$

When the opportunity cost of entry increases exogenously, fewer potential entrants enter and those that do have a higher EPP. Rising EPP therefore provides suggestive evidence of increasing barriers to entry.

---

## Data

**Firm financials.** Revenues, variable costs, and fixed costs come from Compustat, corresponding to accounting revenues, cost of goods sold, and selling, general and administrative costs, respectively.

**Product similarity.** Hoberg and Phillips (2016) provide a time-varying estimate of the matrix of product-based cosine similarities $\mathbf{A}'\mathbf{A}$ between firms, constructed by text-mining the business description section of 10-K forms of all publicly-listed U.S. firms (vocabulary of 61,146 words). Pellegrino (2019) shows how to identify $\mathbf{\Sigma}$ from these cosine similarity data.

**VC-backed startup exits.** Data on initial public offerings (IPOs) and acquisitions of venture capital-backed startups come from the National Venture Capital Association.

---

## Results

### The Shift from IPOs to Acquisitions

IPOs have become a dwindlingly small share of venture capital (VC) exits compared to acquisitions. While IPOs greatly outnumbered acquisitions as the preferred exit for VC-backed startups in the late 1980s and early 1990s, this pattern has entirely reversed. By 2019 there were just over 100 IPOs compared to over 900 acquisitions. This relative decline is unrelated to a decline in the startup rate: the number of VC-backed startups has radically increased over this period. The cause of the IPO decline is not a dearth of startups, but that most VC-backed startups now choose to be acquired by incumbents.

### Rising Barriers to Entry

The entrant productivity premium $\mathrm{EPP}_i$ increased dramatically over the two decades in the sample. The mean EPP doubled from around 10% at the beginning of the sample to over 20% at the end. The median EPP experienced a similarly large increase, rising from around 5% in 1997 to over 8% in 2019. This increase was not driven by outliers. These developments suggest that the opportunity cost of entering and competing with incumbents increased significantly throughout the entire distribution of firms.

### Declining Product Market Centrality of GAFAM

A disproportionately large share of startup acquisitions has occurred in the technology sector. Google/Alphabet, Apple, Facebook/Meta, Amazon, and Microsoft (GAFAM) have acquired hundreds of companies in the last two decades, outpacing other groups of top acquirers.

All of these companies have an exceptionally low product market centrality $\chi_i$, placing them in the bottom percentiles of the distribution of $\chi_i$ among technology firms at the end of the sample. This suggests they supply products with exceptionally unique characteristics that provide tremendous insulation from competitive pressures. Moreover, with the exception of Microsoft, the product market centrality of GAFAM declined significantly over time while their respective profitability increased. Because this percentile rank is computed within the technology sector, the result cannot be driven by a faster rate of productivity growth in technology broadly.

---

## Conclusion

This paper documents a secular shift from IPOs to acquisitions of VC-backed startups, and presents suggestive evidence linking this shift to the aggregate increase in oligopoly power. First, the rising entrant productivity premium suggests that firms face an increasingly high opportunity cost of going public. Second, dominant companies that are disproportionately active in the market for startup acquisitions — particularly GAFAM — have become measurably more insulated from product market competition over the same period. These facts are consistent with the hypothesis that startup acquisitions have contributed to rising oligopoly power in high-tech sectors, although more research is needed to establish a causal nexus.
