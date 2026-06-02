# Search Fatigue

**Bruce I. Carlin** (UCLA Anderson School of Management)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)

*Review of Industrial Organization*, Vol. 54, No. 3, pp. 485–508, May 2019. DOI: 10.1007/s11151-018-9657-5

---

## Abstract

We study markets in which consumer search is not only costly but also tiring. Our model predicts that equilibrium prices are time-varying, exhibits cyclical price dispersion across firms, and that firms over-proliferate their product lines to take advantage of consumer fatigue. We also show that firms voluntarily provide consumer assistance in order to attract tired shoppers. These market outcomes are novel welfare-reducing phenomena that do not arise in the standard search model.

**Keywords:** Consumer search, Fatigue, Product proliferation, Time-varying prices, Cyclical price dispersion.

---

## 1. Model

An infinite horizon economy ($t \in \{0, 1, 2, \ldots\}$) has $n$ firms, each offering a product line of length $\ell_j$ products at a fixed cost of $\kappa$ per product. Each product yields value $\bar{q}$ to the consumer. Firms choose their product line lengths at $t = 0$; thereafter each period has three stages:

1. The consumer decides whether to be a shopper (search for the best price) or not.
2. Firms set prices and choose whether to provide consumer assistance $a_j \in \{0, 1\}$.
3. The consumer purchases.

Consumer **search fatigue** is modeled through a search cost $c(x_{t-1})$ that depends on the number of products examined in the previous period $x_{t-1}$, with $c(0) = 0$, $c(\infty) = \infty$, and $c$ strictly increasing. A consumer who searched extensively last period faces higher costs this period. Consumer assistance at firm $j$ ($a_j = 1$) eliminates within-store search cost.

---

## 2. Main Results

### 2.1 Monopoly Benchmark

**Proposition 1.** The monopoly equilibrium has $\ell^* = 1$, price $p^{1,*} = \bar{q}$ in every period, no consumer search ($s^* = 0$), and no consumer assistance ($a^* = 0$). Firm profit is $\Pi^* = \frac{1}{1-\delta}\bar{q} - \kappa$.

The monopolist has no incentive to proliferate products or provide assistance: there is no competition to drive these strategies.

### 2.2 Oligopoly with Search Fatigue (All-or-Nothing Search)

Define $\bar{L}$ as the smallest integer such that $\bar{q} \leq c(\bar{L})$: the product line length at which a consumer who searched that many products last period finds further search not worthwhile.

**Proposition 2.** Under all-or-nothing search, the unique equilibrium has total product line length $L^* = \sum_j \ell^*_j = \bar{L}$, with:

- **Odd periods** ($t = 1, 3, \ldots$): consumers shop ($s^* = 1$), all firms price at zero ($p^{1,*}_j = 0$), no assistance ($a^*_j = 0$).
- **Even periods** ($t = 2, 4, \ldots$): consumers do not shop ($s^* = 0$), all firms provide assistance ($a_j = 1$), firms charge $p^{1,*}_j = \bar{q}$ for the first product and positive prices for additional products.

Each firm earns $\Pi^*_j = \frac{\delta \bar{q}}{n(1-\delta^2)} - \ell^*_j \cdot \kappa$. Consumer surplus is $U^* = \frac{1}{1-\delta^2}\bar{q}$. Total welfare is $\frac{1}{1-\delta}\bar{q} - L^*\kappa$. The **deadweight loss** relative to the monopoly benchmark is $(L^* - 1)\kappa$, entirely due to product proliferation.

The mechanism: in odd periods firms compete aggressively (Bertrand-style, zero profits) to attract fresh shoppers, fatiguing consumers into extensive searching; in even periods, fatigued consumers are unwilling to search again, allowing firms to extract full surplus. Firms proliferate products beyond $\ell^* = 1$ to make the consumer search sufficiently many products to become fatigued.

### 2.3 Sequential Search Within Stores

**Corollary 1.** Under sequential (within-store) search, each firm optimally sets $\ell^*_j > \bar{L}$. Product proliferation is even greater than under all-or-nothing search. The equilibrium corresponds to a "finding the needle in a haystack" game: firms pack their product lines with decoy products so that the consumer must search extensively within each store to find the best-priced item.

### 2.4 Variable Search Costs

When consumers incur cost $c(x_{t-1}) > 0$ per store visited (not just per product), the Diamond Paradox arises whenever the consumer has a positive search cost: firms can charge strictly positive prices even on the first product.

**Proposition 3.** With variable store-level search costs, the equilibrium has $\ell^*_j = 2$ for all $j$ (total $L^* = 2n$), with the same alternating price pattern as Proposition 2. Each firm earns $\Pi^*_j = \frac{\delta \bar{q}}{n(1-\delta^2)} - 2\kappa$. Consumer surplus is $U^* = \frac{1}{1-\delta^2}\bar{q}$. Total welfare is $\frac{1}{1-\delta}\bar{q} - 2n\kappa$.

---

## 3. Extensions

### 3.1 Heterogeneous Fatigue

When a fraction $\mu_t$ of consumers are shoppers (fatigued fraction $1 - \mu_t$ do not search), firms mix prices in a mixed-strategy equilibrium.

**Proposition 4.** For $\delta \leq \bar{\delta}$, the equilibrium price distribution in period $t$ is

$$F_t(p) = 1 - \left[\frac{(\bar{q}-p)(1-\mu_t)}{n\mu_t}\right]^{1/(n-1)}$$

with lower bound $p^*_t = \bar{q}/\left[\frac{n\mu_t}{1-\mu_t} + 1\right]$. In odd periods $\mu_t = r$ (fraction $r$ shop); in even periods $\mu_t = 1 - r$ (fewer shoppers due to fatigue from prior period). Total product line length remains $L^* = \bar{L}$. Welfare remains $\frac{1}{1-\delta}\bar{q} - \bar{L}\kappa$.

Higher $\mu_t$ (more shoppers) leads to more competitive pricing; lower $\mu_t$ allows higher prices. The cyclical pattern in $\mu_t$ generates cyclical price dispersion.

### 3.2 Brand Loyalty

When a fraction $1 - \lambda$ of consumers have brand loyalty (always purchase from their preferred firm), the effective fraction of price-sensitive shoppers in period $t$ is $\lambda \mu_t$.

**Proposition 5.** The equilibrium price distribution is

$$F_t(p) = 1 - \left[\frac{(\bar{q}-p)(1-\lambda\mu_t)}{n\lambda\mu_t}\right]^{1/(n-1)}$$

with lower bound $p^*_t = \bar{q}/\left[\frac{n\lambda\mu_t}{1-\lambda\mu_t} + 1\right]$. Total product line length remains $L^* = \bar{L}$. Welfare remains $\frac{1}{1-\delta}\bar{q} - \bar{L}\kappa$. Brand loyalty mutes the competitive pressure that shoppers impose on firms, raising equilibrium prices.

---

## 4. Conclusion

When consumer search is not only costly but tiring, markets exhibit cyclical prices, strategic product proliferation, and voluntary consumer assistance — phenomena that do not arise in standard search models. Product proliferation is privately profitable because it raises search costs for consumers in subsequent periods, allowing firms to extract surplus from fatigued shoppers. Consumer assistance is voluntarily provided in even periods precisely to attract consumers who have already been fatigued into not searching. The deadweight loss from equilibrium product proliferation — $(L^* - 1)\kappa$ per period — represents a novel form of market failure rooted in the intertemporal structure of search costs.
