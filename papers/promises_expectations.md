# Promises and Expectations

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Alexander Stremitzer** (ETH Zürich)

*Games and Economic Behavior*, Vol. 106, pp. 161–178, November 2017

---

## Abstract

We study the role of guilt aversion in promise-keeping. In a laboratory experiment, we exogenously manipulate promisors' second-order expectations — their beliefs about promisees' expectations of promisor behavior — while holding first-order expectations constant. We find that higher second-order expectations lead promisors to behave significantly more generously, consistent with a guilt aversion mechanism: promisors are motivated to keep their promises by the anticipated disutility of disappointing the promisee's expectations. We develop and test a conditional guilt aversion model that rationalizes these findings and encompasses earlier experimental results on guilt aversion.

**JEL Codes:** C72, C91, D03, D86, K12.

---

## Background and Motivation

Promises are pervasive in economic life — from employment contracts to informal agreements between friends — yet standard game theory predicts they should have no effect when unenforceable and non-binding. Empirical evidence shows, however, that people frequently keep promises even in one-shot interactions where there is no legal enforcement and no reputational benefit.

One explanation for promise-keeping is **guilt aversion**: promisors anticipate feeling guilty for disappointing a promisee's expectations, and this anticipated guilt acts as a psychological cost that incentivizes compliance. The key mechanism is not the promise per se, but the expectations it generates: by making a promise, a promisor raises the promisee's belief that the promise will be kept, and failing to keep the promise causes guilt proportional to the disappointment inflicted.

This paper tests the guilt aversion mechanism by directly manipulating the key object in the theory: the promisor's **second-order expectations** (the promisor's belief about what the promisee expects the promisor to do).

---

## Experimental Design

### The Trust Game

The experiment uses a modified trust game:

- A **promisee** (investor) decides whether to send a sum of money to the promisor (trustee). If sent, the amount is multiplied.
- The **promisor** (trustee) can optionally make a promise to return a fair share of the money before the promisee makes a decision.
- After observing the promisee's decision, the promisor decides how much to return.

### Manipulation of Second-Order Expectations

The key experimental manipulation varies what promisors are told about promisees' expectations:

- **High expectations condition:** Before making the return decision, the promisor is told (truthfully or by experimental manipulation) that the promisee expects a high return rate.
- **Low expectations condition:** The promisor is told that the promisee expects a low return rate.

First-order expectations (what the promisee actually expects) are held constant across conditions; only the promisor's *belief* about what the promisee expects is varied. This separates the guilt aversion channel (promisor's belief about promisee expectations) from other channels (actual promisee beliefs, social norms, etc.).

### Key Experimental Treatments

| Treatment | Promise made? | Second-order expectations manipulated? |
|---|---|---|
| Baseline | No | No |
| Promise only | Yes | No |
| High expectations | Yes | Yes (high) |
| Low expectations | Yes | Yes (low) |

---

## Results

### Main Finding: Guilt Aversion Drives Promise-Keeping

The central result is that **higher second-order expectations lead to higher promisor generosity**. Promisors who believe the promisee expects a high return transfer significantly more money than promisors who believe the promisee expects a low return, even when the promise and the actual promisee expectations are held constant.

This finding is consistent with guilt aversion: promisors who anticipate a larger disappointment (because the promisee has high expectations) are more motivated to avoid that guilt by fulfilling the promise.

### Guilt Aversion vs. Other Mechanisms

The experimental design allows the authors to rule out alternative explanations:

- **Social norms:** Holding actual promisee beliefs constant eliminates the possibility that promisors are responding to the social expectations of the experimenter or norm of promise-keeping per se.
- **Intrinsic motivation:** The manipulation of second-order expectations (not first-order expectations) shows that it is the promisor's *belief* about promisee expectations, not the actual expectations, that drives behavior.
- **Strategic reputation:** One-shot interactions without repetition eliminate reputational concerns.

### Financial Literacy and Promise-Keeping

More financially sophisticated and better-educated subjects show stronger guilt aversion responses, suggesting that the capacity for perspective-taking and belief-based reasoning amplifies the guilt aversion effect.

---

## Theoretical Framework: Conditional Guilt Aversion

The authors develop a **conditional guilt aversion model** in which a promisor's utility is:

$$U = v(\text{payoff}) - \gamma \max\{E[\pi_j] - \pi_j, 0\}$$

where $E[\pi_j]$ is the promisor's second-order expectation of what the promisee expects to receive, $\pi_j$ is the actual payoff delivered to the promisee, and $\gamma \geq 0$ is the guilt aversion coefficient.

The "conditional" aspect refers to the conditioning of guilt on whether a promise was made: guilt is activated when the promisor has explicitly made a promise, creating elevated expectations. Without a promise, the reference point for the promisee's expectations is lower, generating less guilt from the same transfer level.

This model:
1. Predicts higher transfers when second-order expectations are higher
2. Rationalizes the experimental results across all treatments
3. Encompasses earlier guilt aversion models (Battigalli and Dufwenberg) as special cases
4. Generates the prediction that promises amplify guilt aversion by raising the reference point

---

## Conclusion

Promises are kept because breaking them causes anticipated guilt, proportional to the extent to which the promisee's expectations are disappointed. The paper provides the first direct experimental evidence that **second-order expectations** — promisors' beliefs about promisees' expectations — drive promise-keeping through a guilt aversion mechanism, independent of actual promisee beliefs or social norms. These findings have implications for the design of contracts, the foundations of informal agreements, and the psychological underpinnings of trust in economic relationships.
