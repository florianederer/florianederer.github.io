# Feedback and Motivation in Dynamic Tournaments

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)

*Journal of Economics & Management Strategy*, Vol. 19, No. 3, pp. 733–769, Fall 2010

---

## Abstract

This paper studies the role of organizational feedback mechanisms in a dynamic tournament with heterogeneous agents. Its main contribution is the consideration of heterogeneity among agents, a generalization that opens the way for the analysis of learning on behalf of the agents as well as motivational measures taken by the firm. In models in which ability plays no role or enters additively, the choice between feedback policies depends on the third derivative of the disutility of effort. The analysis becomes much richer in content once one considers a situation in which beliefs about ability directly impact each worker's effort choice. In such a setting, interim performance evaluations are not merely a mechanism by which information about past performance is transmitted to workers: they also represent an intentional attempt by organizations to influence the morale of their workers. The paper discusses several consequences of interim performance evaluations including signal-jamming and the motivation effect, as well as the efficient sorting of workers that the motivation effect induces.

**JEL Codes:** D82, D83, J33, J41, M52.

---

## 1. Model

Two risk-neutral agents $i \in \{A, B\}$ compete in a two-period tournament. In each period $t \in \{1, 2\}$, agent $i$ produces output

$$x_t^i = h(a^i, e_t^i) + \varepsilon_t^i,$$

where $a^i$ is the agent's ability (unknown to both agents and the principal), $e_t^i$ is effort chosen by the agent, and $\varepsilon_t^i$ is noise. Abilities are independently and identically distributed with mean $\mu$. The noise difference $\Delta\varepsilon_t \equiv \varepsilon_t^A - \varepsilon_t^B$ has CDF $F(\cdot)$ and density $f(\cdot)$ symmetric and unimodal at 0. The cost of effort $c(\cdot)$ is strictly convex with $c'(0) = 0$.

At the end of period 1 the principal observes the output difference $\Delta x_1 \equiv x_1^A - x_1^B$. Under a **no-feedback** policy this information is withheld; under a **full-feedback** policy it is revealed to both agents before period 2. Agent $i$'s payoff is

$$U^i = \Pr(x_1^i + x_2^i > x_1^j + x_2^j) - c(e_1^i) - c(e_2^i).$$

---

## 2. No Motivation Effect: Additive Ability

When $x_t^i = a^i + e_t^i + \varepsilon_t^i$, ability enters additively and does not affect the marginal benefit of effort. Under no feedback, the symmetric equilibrium first-order condition is

$$c'(e^*) = E_{a^A, a^B, \Delta\varepsilon_1}[f(2\Delta a + \Delta\varepsilon_1)], \tag{1}$$

where $\Delta a \equiv a^A - a^B$. Under full feedback, the second-period FOC conditional on $\Delta x_1$ is

$$c'(\tilde{e}_2(\Delta x_1)) = E_{a^A, a^B}[f(\Delta x_1 + \Delta a) \mid \Delta x_1]. \tag{2}$$

**Lemma 1.** The first-period effort under feedback satisfies the same FOC as under no feedback:

$$c'(\tilde{e}_1) = E_{a^A, a^B, \Delta\varepsilon_1}[f(2\Delta a + \Delta\varepsilon_1)]. \tag{4}$$

**Proposition 1.** First-period effort levels are identical under both feedback policies. Expected second-period effort under full feedback is lower (higher) than under no feedback if $c'$ is convex (concave), and equal if the cost function is quadratic.

The comparison of second-period effort reflects two competing effects. The **noise reduction effect** increases incentives because feedback reduces the uncertainty in the second period. The **evaluation effect** (lack-of-competition effect) reduces incentives because feedback reveals the magnitude of the performance gap, and agents far behind or far ahead exert less effort.

---

## 3. Motivation Effect: Multiplicative Ability

When $x_t^i = a^i e_t^i + \varepsilon_t^i$, ability directly multiplies effort, so beliefs about ability affect the marginal benefit of effort. This creates a **motivation effect**: feedback induces agents to update their beliefs about their own ability, thereby changing the marginal return to effort in period 2.

### 3.1 Uniform Model

Assume the noise difference $\Delta\varepsilon_1$ is uniformly distributed on $[-m, m]$, the cost function is quadratic $c(e_t^i) = \frac{k}{2}(e_t^i)^2$, and ability has support $[0, \bar{a}]$ with log-concave density and mean $\mu$.

Under no feedback, the symmetric equilibrium FOC is

$$c'(e^*) = \frac{\mu}{2m}. \tag{5}$$

Under full feedback, the second-period FOCs are asymmetric across agents:

$$c'(\tilde{e}_2^A(\Delta x_1)) = \frac{1}{2m} E[a^A \mid \Delta x_1], \tag{6a}$$

$$c'(\tilde{e}_2^B(\Delta x_1)) = \frac{1}{2m} E[a^B \mid \Delta x_1]. \tag{6b}$$

A favorable first-period output difference $\Delta x_1 > 0$ raises agent $A$'s posterior belief about his own ability and thus his second-period effort, while lowering agent $B$'s. This sorting of effort by ability is the motivation effect.

The first-period FOC under full feedback is

$$c'(\tilde{e}_1) = \frac{1}{2m}\left\{\mu - E_{a^A, a^B, \Delta\varepsilon_1}\left[a^B \frac{d\tilde{e}_2^B(\Delta x_1)}{de_1^A}\right]\right\}. \tag{8}$$

The additional term captures a **signal-jamming effect**: agent $A$ has an incentive to exert additional first-period effort to shift $\Delta x_1$ in his favor, causing agent $B$ to revise his ability beliefs downward and reduce his second-period effort. This is analogous to the career concerns mechanism in Holmstrom (1982).

**Proposition 2.** If the noise difference is uniformly distributed, first-period effort and expected first-period output are higher under full feedback than under no feedback.

**Proposition 3.** If the noise difference is uniformly distributed and the cost function is quadratic, expected second-period effort is equal under both policies. However, expected second-period output is higher under full feedback because feedback sorts workers by ability: more able agents exert more effort and less able agents exert less, and with complementarity between ability and effort, average output rises.

**Corollary 1.** If the noise difference is uniformly distributed and the cost function is quadratic, full feedback leads to higher expected overall output than no feedback.

### 3.2 Normal Model

To illustrate the **evaluation effect** — which is absent when noise is uniform because the uniform density $f'(\cdot) = 0$ within its support — the paper analyzes a normal model in which all random variables are jointly normally distributed:

$$\begin{pmatrix} a^A \\ a^B \\ \Delta\varepsilon_1 \\ \Delta\varepsilon_2 \end{pmatrix} \sim N\left(\begin{pmatrix} \mu \\ \mu \\ 0 \\ 0 \end{pmatrix}, \begin{pmatrix} \sigma^2 & 0 & 0 & 0 \\ 0 & \sigma^2 & 0 & 0 \\ 0 & 0 & 2\tau^2 & 0 \\ 0 & 0 & 0 & 2\tau^2 \end{pmatrix}\right).$$

Under no feedback the symmetric equilibrium satisfies

$$ke^* = \frac{\phi(0)}{\sqrt{\text{var}(\Delta x_1 + \Delta x_2)}} \cdot \mu, \tag{9}$$

where $\phi$ is the standard normal PDF. Under full feedback the second-period FOCs yield asymmetric effort levels whose right-hand sides contain three terms: (i) the evaluation effect (higher effort when the contest is close), (ii) the motivation effect (higher effort for the agent with a favorable $\Delta x_1$), and (iii) their interaction. When $\Delta x_1 = 0$ the effort choice is symmetric; when $\sigma^2 = 0$ the motivation effect vanishes.

### 3.3 Comparison and Discussion

In the normal model, whether full feedback dominates no feedback depends on the magnitude of $\sigma^2$ relative to $\tau^2$. For $\sigma^2 = 1$, a full-feedback policy leads to lower expected second-period effort (evaluation effect) but higher first-period effort (signal-jamming) and higher expected second-period output (motivation and sorting effects). For $\sigma^2 = 0.5$, both expected aggregate effort and output are lower under full feedback. When $\sigma^2 = 0$, the two policies are identical. There is therefore no unambiguous ranking of feedback policies in the normal model.

The analysis highlights a fundamental distinction between two types of information in interim performance appraisals: (i) information about how the employee can improve performance and develop skill — which is purely motivating — and (ii) information about a worker's future prospects — which creates an uneven playing field and may reduce competitive pressure. This distinction corresponds to the tension in the HR literature between "training and development" and "evaluation." Many organizations explicitly separate these functions: consulting firms, for instance, conduct developmental assessments that are explicitly stated not to affect evaluation outcomes.

---

## 4. Conclusion

This paper studies the role of organizational feedback mechanisms in dynamic tournaments. Its main contribution is the analysis of heterogeneous agents, which opens up the possibility of a motivation effect and efficient sorting. When ability and effort are complementary, interim performance feedback sorts effort by ability and generates implicit incentives through signal-jamming, both of which raise first-period output. At the same time, the evaluation effect from revealing competitive position can reduce second-period effort incentives. The paper does not provide an unequivocal endorsement of interim performance evaluations: feedback motivates some employees while demotivating others, and the net effect depends on the distribution of performance gaps and the importance of the motivation effect relative to the evaluation effect. Cross-industry variation in the prevalence of formal performance appraisals is consistent with this prediction — industries where the sorting and motivation effects are particularly important (such as professional services) are more likely to use interim evaluations.
