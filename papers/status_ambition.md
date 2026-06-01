# Interpersonal Comparison, Status and Ambition in Organizations

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Andrea Patacconi** (University of Aberdeen)

*Journal of Economic Behavior and Organization*, Vol. 75, No. 2, pp. 348–363, August 2010

---

## Abstract

We study the effects of status concerns and ambition on incentives in tournaments. Status concerns — modeled as reference-dependent preferences over relative wages — increase effort but create asymmetries between promotion-based and demotion-based tournament formats. We show that promotion-based tournaments generate higher firm profits despite eliciting lower effort for a given prize spread, because the optimal prize can be set lower. Ambitious workers, who set high internal reference points, exert more effort than their non-ambitious counterparts, but the optimal organizational response depends on whether ambitious and non-ambitious workers are segregated or mixed across tournaments.

**JEL Codes:** J31, J41, M12, M52.

---

## Theoretical Framework

### The Tournament Model

A firm employs $N$ risk-neutral agents who compete in a tournament for prizes. Each agent $i$ chooses effort $e_i$, which determines output. The highest-performing agents receive the high wage $w_H$ and are promoted; the lowest-performing agents receive the low wage $w_L$ and are demoted (or retained at a lower level).

### Status Concerns and Reference-Dependent Preferences

Agents care about both their absolute wage and their **status** relative to a reference wage $w^R$. The reference wage is determined endogenously as the modal group's wage — the wage received by the majority of agents.

Agent $i$'s expected utility is:

$$Eu_i(e_i) = \Pr(i \in W)[w_H + \beta(w_H - w^R)] + \Pr(i \in L)[w_L + \alpha(w_L - w^R)] - c(e_i)$$

where:
- $W$ is the set of winners (promoted agents), $L$ is the set of losers (demoted agents)
- $\beta \geq 0$ is the gain sensitivity (utility boost from earning above the reference wage)
- $\alpha \geq 0$ is the loss sensitivity (disutility from earning below the reference wage), with $\alpha \geq \beta$
- $c(e_i)$ is a convex cost-of-effort function

The asymmetry $\alpha \geq \beta$ captures loss aversion: agents suffer more from falling below the reference wage than they gain from exceeding it.

### Promotion-Based vs. Demotion-Based Tournaments

The model distinguishes two tournament formats based on how the reference wage is determined:

**Promotion-based tournament:** The majority of agents are retained at the low wage $w_L$; a minority are promoted to $w_H$. The reference wage is $w^R = w_L$ (the modal wage). Winning generates a status gain $\beta(w_H - w_L) > 0$; losing generates no status loss (since $w_L = w^R$).

**Demotion-based tournament:** The majority of agents are promoted to $w_H$; a minority are demoted to $w_L$. The reference wage is $w^R = w_H$. Winning generates no status gain (since $w_H = w^R$); losing generates a status loss $\alpha(w_L - w_H) < 0$.

---

## Main Results

### Proposition 1 (Status Increases Effort)

Status concerns increase equilibrium effort relative to the benchmark without status concerns ($\alpha = \beta = 0$). For any fixed prize spread $w_H - w_L$:

- **Demotion-based tournaments elicit higher effort** than promotion-based tournaments, because the loss-aversion effect ($\alpha$) at the bottom is stronger than the gain effect ($\beta$) at the top, and in demotion-based settings the majority faces a potential status loss.

### Proposition 2 (Promotion-Based Tournaments Are More Profitable)

Despite eliciting lower effort for a given prize spread, **promotion-based tournaments generate higher firm profits** than demotion-based tournaments. The intuition is that the firm can elicit the same effort level at a lower cost under the promotion-based format: since promotion generates a status gain, agents value winning more, so the monetary prize needed to incentivize effort is lower.

The asymmetric effects of loss aversion (large demotion pain vs. modest promotion gain) mean the principal can exploit the gain channel at low cost under promotion but must pay for the loss channel under demotion.

### Proposition 3 (Optimal Effort Ranking)

When each tournament format is optimally designed (choosing $w_H$ and $w_L$ to maximize profits), the ranking of equilibrium effort levels is:

$$e^{P*} > e^{ND*} > e^{D*}$$

where $e^{P*}$ is effort under optimal promotion-based tournaments, $e^{ND*}$ under optimal no-demotion (mixed) formats, and $e^{D*}$ under optimal demotion-based tournaments.

### Proposition 4 (Promotion-Based Dominates)

Among all tournament formats, the **promotion-based tournament maximizes firm profits**. The proof shows that the gain sensitivity channel is cheaper to exploit than the loss channel, so the profit-maximizing firm always prefers a format in which winners gain status relative to a "loser" reference point rather than a format in which losers suffer a status loss.

### Proposition 5 (Maximize Promotions, Minimize Demotions)

Given a fixed reference wage constraint, the optimal contract structure **maximizes the number of promotions and minimizes the number of demotions**, subject to the constraint that the reference wage remains at the lower level. This is the efficient way to deploy status incentives: give as many agents as possible the opportunity to gain status while keeping the reference point low.

---

## Section 4: Ambition

### Ambitious vs. Non-Ambitious Workers

An **ambitious worker** sets a high internal reference point $w^R_A$ independent of the organizational wage structure. A **non-ambitious worker** uses the modal wage as the reference point, as in the baseline model.

Ambitious workers who set $w^R_A > w_H$ suffer a status loss even when promoted, because they compare themselves to an aspiration wage above what the organization offers. This creates higher intrinsic motivation: **ambitious workers exert more effort** than non-ambitious workers for any given prize spread.

Key results on effort comparisons:
- $e_{A,A} > e_{A,NA}$: an ambitious worker exerts more effort when matched against another ambitious worker than against a non-ambitious one
- $e_{NA,NA} > e_{NA,A}$: a non-ambitious worker exerts more effort when matched against another non-ambitious worker than against an ambitious one

The second result reflects a discouragement effect: non-ambitious workers lower effort when facing an ambitious rival who will exert very high effort regardless.

### Segregated vs. Mixed Tournaments

**Segregated tournaments** (ambitious vs. ambitious; non-ambitious vs. non-ambitious) yield higher average effort than **mixed tournaments** (ambitious vs. non-ambitious) under most conditions. The discouragement effect on non-ambitious workers in mixed tournaments reduces their effort below what they would exert in homogeneous competition.

---

## Section 5: Ambition and Ability

### Correlated Ambition and Ability

When ambition and ability are positively correlated (more able workers are also more ambitious), segregated tournaments are efficient: ambitious-able workers compete together, and the firm benefits from high effort in the top tier.

If the cost function satisfies $c''' \leq 0$, a positive correlation between ambition and ability may lead to **lower average effort** than under negative correlation or independence, because high-ability ambitious workers are less responsive to marginal incentives when their base effort is already high.

### Proposition 9 (Segregated Beats Mixed on Average)

Segregated tournaments generate higher average effort than mixed tournaments across the workforce. Mixed tournaments are preferred by the firm only when there is a large selection benefit $T$ — i.e., when mixing ambitious and non-ambitious workers generates information that allows the firm to make better promotion decisions that outweigh the effort cost from the discouragement effect.

---

## Conclusion

Status concerns and ambition generate complex incentive effects in organizations. While demotion threats elicit high effort for a given prize spread, promotion-based tournaments are more profitable because the status gain from promotion is cheaper to provide than the status loss from demotion is to compensate. Ambitious workers exert high effort but can discourage less ambitious colleagues in mixed competitions. The optimal organizational design segregates ambitious and non-ambitious workers and maximizes the scope for status gains through promotion rather than demotion threats.
