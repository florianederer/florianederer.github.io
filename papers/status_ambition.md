# Interpersonal Comparison, Status and Ambition in Organizations

**Florian Ederer** (Anderson School of Management, University of California at Los Angeles)
**Andrea Patacconi** (University of Aberdeen Business School)

*Journal of Economic Behavior & Organization*, Vol. 75, pp. 348–363, 2010

---

## Abstract

This paper analyzes the effect of introducing status concerns into a model of tournament competition. It emphasizes the role of reference groups and the optimal number of winners and losers in a tournament. Because firms must compensate employees for the disutility of low status, they may be reluctant to explicitly identify losers. This rationalizes the prevalence of compensation systems that reward winners without explicitly identifying losers — promotion-based tournaments — which are shown to dominate demotion-based schemes in terms of firm profits. The paper also shows that ambitious workers always exert more effort than unambitious workers, that both types work harder in segregated than in mixed tournaments, and that ambitious workers may perversely discourage effort by their non-ambitious rivals.

**JEL Codes:** J31, J41.

**Keywords:** Reference-dependent preferences, Status, Ambition, Tournaments.

---

## 1. Model

$N$ agents compete in a tournament. $N_W \geq 1$ winners receive a high wage $w_H$ and the remaining $N_L = N - N_W$ receive a low wage $w_L$. Status concerns are modeled through a reference wage $w^R$: the modal group's wage serves as the reference point, so $w^R = w_H$ if winners form the modal group (demotion-based: many winners, few losers) and $w^R = w_L$ if losers form the modal group (promotion-based: few winners, many losers). Agent $i$'s expected utility is

$$Eu_i(e_i) = \Pr(i \in W)[w_H + \beta(w_H - w^R)] + \Pr(i \in L)[w_L + \alpha(w_L - w^R)] - c(e_i), \tag{1}$$

where $\alpha \geq \beta \geq 0$ measure the sensitivity to status losses and gains respectively, and $c(\cdot)$ is strictly increasing and convex. The asymmetry $\alpha \geq \beta$ reflects loss aversion: the disutility of having low status exceeds the utility of having high status.

The firm's objective is to maximize expected profits

$$\max E\Pi = V\sum_{i=1}^N e_i - N_W w_H - N_L w_L \tag{2}$$

subject to incentive constraints

$$\frac{\partial \Pr(i \in W)}{\partial e_i}\left[(w_H - w_L) + \alpha(w^R - w_L) + \beta(w_H - w^R)\right] = c'(e_i). \tag{3}$$

---

## 2. Promotion-Based vs. Demotion-Based Tournaments

**Promotion-based tournament** ($w^R = w_L$, few winners): The incentive constraint becomes

$$\frac{\partial \Pr(i \in W)}{\partial e_i}(1 + \beta)(w_H - w_L) = c'(e_i), \tag{5b}$$

and firm profits are

$$E\Pi^{PB} = VNe - N[\bar{u} + c(e)] + N_W^{PB}\beta(w_H - w_L). \tag{5a}$$

The status gain from winning (captured by $\beta$) saves the firm money because it reduces the wage premium needed to provide incentives.

**Demotion-based tournament** ($w^R = w_H$, few losers): The incentive constraint becomes

$$\frac{\partial \Pr(i \in W)}{\partial e_i}(1 + \alpha)(w_H - w_L) = c'(e_i), \tag{6b}$$

and firm profits are

$$E\Pi^{DB} = VNe - N[\bar{u} + c(e)] - (N - N_W^{DB})\alpha(w_H - w_L). \tag{6a}$$

The status loss from demotion (captured by $\alpha$) costs the firm money because it must compensate workers for the disutility of low status.

**Proposition 1.** For any given wage spread, (i) equilibrium effort is higher with status concerns than without; and (ii) effort is higher in a demotion-based than a promotion-based tournament if $\alpha - \beta$ is sufficiently large.

**Proposition 2.** Expected profits are higher in the promotion-based than in the demotion-based tournament, both for a fixed effort level and when effort is optimally chosen:

$$E\Pi^{PB}(e^{PB}) \geq E\Pi^{PB}(e^T) > E\Pi^T > E\Pi^{DB}(e^{DB}).$$

Although demotion-based tournaments can elicit higher effort, they do so only by imposing larger status costs on losers, which must be compensated by the firm and outweigh the productivity benefits.

**Proposition 3.** When wage spreads are chosen optimally, equilibrium effort is highest in the promotion-based tournament, lower in the standard tournament (no status concerns), and lowest in the demotion-based tournament.

**Proposition 4.** Firm profits are higher in a promotion-based tournament (with reference group) than in a standard tournament without reference groups; promotion-based tournaments dominate all tournament scenarios.

---

## 3. Promotions and Demotions with Three Tiers

When the firm can promote, demote, or retain workers (three wage levels $w_H > w_M > w_L$, with $N_W$ promoted and $N_L$ demoted), the reference wage is the modal group's wage.

**Proposition 5.** It is optimal to set $\Delta w^- = 0$ or $N_L = 0$ (or both), and to set $N_W = (N - D)/2$, $N_M = (N + D)/2$, with wages set so that the participation constraint binds. The firm should maximize the number of promotions and minimize the number of demotions.

**Proposition 6.** Without loss of generality, attention can be restricted to tournaments in which $w^R = w_M$, that is, where the middle tier forms the reference group.

These results explain why firms commonly reward winners without explicitly identifying losers: promotion without demotion minimizes the status costs that the firm must compensate.

---

## 4. Ambition

An **ambitious** worker sets his reference wage equal to the high wage, $w^R_A = w_H$, regardless of the tournament format; an **unambitious** worker sets $w^R_{NA} = w_L$. In a two-agent setting the FOCs are:

- Ambitious vs. unambitious opponent: $g(0)(1 + \alpha)\Delta w = c'(e_{A,NA})$
- Unambitious vs. ambitious opponent: $g(0)(1 + \beta)\Delta w = c'(e_{NA,A})$

**Proposition 7.** Ambitious workers always exert more effort than unambitious workers. Both types exert more effort in segregated tournaments (matched against like types) than in mixed tournaments:

$$e_{A,A} > e_{A,NA}, \quad e_{NA,NA} > e_{NA,A}, \quad e_{A,NA} > e_{NA,A}.$$

The ambitious worker's high reference point magnifies both the gain from winning and the loss from losing, generating stronger incentives. However, when an unambitious worker is matched against an ambitious opponent, the unambitious worker reduces effort because the ambitious opponent's strong incentives make competition less attractive — a discouragement effect.

---

## 5. Ambition and Ability

When output is $x_i = a_i + e_i + \varepsilon_i$ with ability $a_i \in \{a_L, a_H\}$ correlated with ambition (correlation parameter $p = \Pr(H \mid A) = \Pr(L \mid NA)$):

**Proposition 8.** Ambitious workers always exert more effort. The probability of promoting the more able worker is strictly increasing in $p$. If $c'''(\cdot) \leq 0$, average effort is lower when $p = 1$ (ability and ambition perfectly positively correlated) than when $p = 0$ (perfectly negatively correlated).

**Proposition 9.**
- (i) Average effort is higher in segregated than mixed tournaments. The benefit of promoting the right worker can be higher in either tournament format.
- (ii) If $p = 0$, mixed tournaments are optimal when selection is important ($T$ large) and the ability gap $a$ is sufficiently large relative to $\alpha - \beta$.
- (iii) If $p = 1$, mixed tournaments are optimal when selection is sufficiently important ($T$ sufficiently large).

When ambition and ability are negatively correlated, the firm faces a tradeoff: mixed tournaments reduce average effort but may improve selection by placing high-ability workers against ambitious rivals, inducing more balanced competition.

---

## 6. Conclusion

Introducing status concerns into tournament models has substantial implications for incentive provision. Because status losses are more costly than status gains are valuable ($\alpha \geq \beta$), firms optimally use promotion-based compensation systems that reward winners without explicitly identifying losers. Demotion-based systems generate higher effort but impose status costs that more than offset the efficiency gains. Ambitious workers exert more effort in all settings, but may discourage non-ambitious rivals in mixed tournaments, creating a tradeoff between effort elicitation and selection efficiency that depends on the correlation between ambition and ability and on the importance of selecting the most able worker.
