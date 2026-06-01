# Gaming and Strategic Opacity in Incentive Provision

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Richard Holden** (University of New South Wales)
**Margaret Meyer** (University of Oxford; CEPR)

*RAND Journal of Economics*, Vol. 49, No. 4, pp. 819–854, Winter 2018

---

## Abstract

We study optimal incentive provision when an agent has private information about the relative costs of performing two complementary tasks and can game deterministic contracts by focusing effort on the most heavily rewarded task. We show that the principal can profitably exploit strategic opacity — deliberately withholding information about which task will be rewarded — to reduce gaming. Two forms of randomization are analyzed: ex ante randomization (EAR), which randomizes the contract before effort is chosen, and ex post randomization (EPR), which randomizes after outputs are observed. EPR dominates EAR when tasks are sufficiently complementary. We characterize when random contracts dominate all deterministic contracts.

**JEL Codes:** D82, D86, J33, M52.

---

## Model

### Setup

A principal hires a risk-averse agent to perform two tasks. Output on task $j$ is:

$$x_j = e_j + \varepsilon_j, \quad j = 1, 2$$

where $e_j$ is effort and $(\varepsilon_1, \varepsilon_2) \sim N(0, \rho\sigma^2)$ with correlation $\rho$.

### Agent Types and Costs

The agent has **private information** about his type, which determines relative task costs:

- **Type-1 agent:** $c_1(e_1, e_2) = \frac{1}{2}(e_1 + \lambda e_2)^2$, with $\lambda \geq 1$. Task 2 is relatively costly.
- **Type-2 agent:** $c_2(e_1, e_2) = \frac{1}{2}(\lambda e_1 + e_2)^2$. Task 1 is relatively costly.

The parameter $\lambda \geq 1$ measures the degree of type asymmetry; $\lambda = 1$ corresponds to homogeneous agents.

### Principal's Payoff

The principal's benefit from effort is:

$$B(e_1, e_2) = \min\{e_1, e_2\} + \frac{1}{\delta} \max\{e_1, e_2\}$$

where $\delta \geq 1$ is a complementarity parameter. As $\delta \to \infty$, tasks become perfect complements (only the minimum effort matters); when $\delta = 1$, tasks are perfect substitutes.

### Contracts

The principal offers a linear contract $w = \alpha + \beta_1 x_1 + \beta_2 x_2$. Because the agent knows his type, a deterministic contract with $\beta_1 \neq \beta_2$ induces gaming: each agent type focuses effort on the more heavily rewarded task.

---

## Deterministic Contracts

Four benchmark deterministic contracts are characterized:

| Contract | Description |
|---|---|
| **SD (Symmetric)** | $\beta_1 = \beta_2 = \beta$; equal weight on both tasks |
| **OT (One Task)** | $\beta_1 = \beta$, $\beta_2 = 0$; reward only task 1 |
| **OA (One Agent Type)** | Asymmetric contract optimal for one type, ignoring the other |
| **AD (Asymmetric)** | $\beta_1 = \lambda \beta_2$; incentive ratio equals cost ratio |

Under SD, both types exert equal effort on both tasks, but effort is lower than first-best because neither type is rewarded for their comparative advantage. Under OT or AD, one agent type games the contract by concentrating effort on the rewarded task, leaving the other task neglected.

The key tension: deterministic contracts that try to elicit balanced effort invite gaming from agents who know their type; contracts that accept gaming concentrate effort suboptimally.

---

## Randomized Contracts

### Ex Ante Randomization (EAR)

Before effort is chosen, the principal publicly commits to reward task 1 with probability $p$ and task 2 with probability $1-p$, each at rate $\beta$.

Under EAR, each agent type must exert effort on both tasks without knowing which will be rewarded. The agent cannot game the contract because the rewarded task is not yet determined.

**Proposition 1.** The optimal EAR sets $p = 1/2$ (equal randomization). Equilibrium effort satisfies:

$$\bar{e}^{EAR} + \lambda \underline{e}^{EAR} = \frac{\beta}{\lambda + 1}$$

where $\bar{e}$ is effort on the agent's favored task and $\underline{e}$ is effort on the costly task. The relationship between $\bar{e}$ and $\underline{e}$ is given by:

$$\lambda = \exp\left[r\beta(\bar{e}^{EAR} - \underline{e}^{EAR})\right]$$

where $r$ is the agent's coefficient of absolute risk aversion. The gap between task efforts is positive but bounded by risk aversion.

### Ex Post Randomization (EPR)

After outputs $x_1$ and $x_2$ are observed, the principal pays:

$$w = \min\{\alpha + \beta x_1,\; \alpha + \beta x_2\}$$

The agent receives the lower of the two task-specific payoffs. This creates incentives to balance effort across tasks: an agent who neglects one task bears a penalty regardless of performance on the other.

**Proposition 2.** EPR effort satisfies the same first-order condition as EAR:

$$\bar{e}^{EPR} + \lambda \underline{e}^{EPR} = \frac{\beta}{\lambda + 1}$$

However, EPR induces a **smaller effort gap** $\bar{e} - \underline{e}$ than EAR, because EPR creates stronger incentives to balance effort: a high output on task 1 is worthless if task 2 output is low. Under EAR, the randomization resolves before effort is chosen, so agents know which task they are rewarded for.

**Proposition 3.** For $\delta \geq \lambda$ (tasks are sufficiently complementary relative to the degree of agent heterogeneity), **EPR generates strictly higher profit than EAR**. When complementarity is high, the principal values balanced effort strongly, and EPR's tighter effort balancing is more valuable.

---

## When Are Deterministic Contracts Optimal?

**Proposition 4.** When $\lambda = 1$ (homogeneous agents with no type asymmetry), the SD contract is optimal — randomization provides no benefit.

**Proposition 5.** When task complementarity is sufficiently low ($\delta \leq \lambda$), a corner solution deterministic contract (OT or OA) dominates random contracts. If complementarity is low, concentrating effort on one task is efficient, and the gaming problem is less costly.

**Proposition 6.** When the asymmetric contract AD perfectly accounts for cost differences, it may dominate randomization for intermediate complementarity values. However, AD requires the principal to know the agent's type, which conflicts with the private information assumption.

---

## When Are Random Contracts Optimal?

Three environments where random contracts strictly dominate all deterministic contracts:

1. **Near-homogeneous agents ($\lambda \to 1^+$):** When types are nearly identical, deterministic contracts induce near-zero gaming, but EPR provides modest balancing benefits at no significant cost. For high complementarity, EPR dominates.

2. **Perfect correlation of task noise ($\rho = 1$):** When outputs are perfectly correlated, symmetric deterministic contracts provide no information about relative task efforts. EPR breaks this symmetry by making the agent's payoff depend on the minimum output, restoring incentives for balance.

3. **High risk aversion ($r \to \infty$):** Highly risk-averse agents strongly prefer balanced income streams. EPR, which penalizes imbalanced outputs, harnesses this preference to induce balanced effort at lower cost than any deterministic contract.

---

## Conclusion

Strategic opacity in incentive provision — deliberately withholding information about which task will be rewarded — can improve principal welfare when agents have private information about task costs and can game deterministic incentive schemes. Ex post randomization (EPR) dominates ex ante randomization (EAR) when tasks are sufficiently complementary, because EPR more tightly links rewards to balanced effort. Random contracts are optimal when agents are nearly homogeneous, task noise is highly correlated, or agents are highly risk-averse. These results offer a rationale for the use of discretionary bonuses, holistic performance reviews, and other opaque incentive schemes in organizations facing multitasking problems with private agent information.
