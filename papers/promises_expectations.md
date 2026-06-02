# Promises and Expectations

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Alexander Stremitzer** (UCLA School of Law)

*Games and Economic Behavior*, Vol. 106, pp. 161–178, November 2017

---

## Abstract

We use a laboratory experiment to provide the first direct test of the hypothesis that people keep promises because they expect to feel guilty when they disappoint their promisee's expectations. We exogenously vary promisors' second-order beliefs (their beliefs about promisees' expectations of promisor performance) while holding constant the promissory link and first-order beliefs. We find that higher second-order beliefs lead to significantly higher performance, consistent with the guilt aversion hypothesis. We propose a conditional guilt aversion model — in which guilt is activated only when a promise is made — and show that this model is consistent with the data.

**JEL Codes:** A13, C72, C91, D03, D64, D80, K12.

**Keywords:** Promises, Expectations, Beliefs, Contracts, Guilt aversion.

---

## 1. Experimental Design

### 1.1 Game Structure

The experiment uses a modified dictator game. Subject A (the dictator/promisor) can send B (the receiver/promisee) a free-form written message that is one of three types: no message, empty talk, or a promise. Subject B then decides whether to opt in or opt out. If B opts in, Nature selects a reliability device that is either reliable ($\rho = 5/6$) or unreliable ($\rho = 1/6$), revealed to both subjects. Subject A alone learns the state $\theta \in \{0, 1\}$ (can or cannot perform). A then chooses a contribution $a \in \{$Don't Perform, $1/4$, $1/2$, $3/4$, Perform$\}$. Payoffs are:

$$\pi_A = 14 - 4a, \quad \pi_B = 12a.$$

The key manipulation is the reliability device $\rho$: when the device is reliable ($\rho = 5/6$), a given message generates higher second-order beliefs in A (A believes B expects more), whereas when it is unreliable ($\rho = 1/6$), the same message generates lower second-order beliefs.

### 1.2 Procedures

20 sessions were conducted at CASSEL (UCLA), with 280 subjects (undergraduate students). Subjects completed 2 practice rounds followed by 8 paying rounds. The reliability device type was elicited using the strategy method (subjects made decisions for both reliability states before learning which applied). Beliefs were incentivized using a binarized scoring rule. Show-up fee: $5.

---

## 2. Results

### 2.1 Main Effect: Second-Order Beliefs Drive Performance

When a promise was made, average contribution was $\$5.76$ under the reliable device ($\rho = 5/6$) versus $\$5.28$ under the unreliable device ($\rho = 1/6$), a significant difference ($p < 0.01$). When no promise was made, there was no significant difference between reliability conditions, ruling out the device affecting performance through channels other than promise-keeping.

The effect of the promissory link dwarfs the effect of the device: average contribution under a promise was $\$0.56$ per unit compared to $\$0.38$ under empty talk and $\$0.38$ with no message ($p < 0.01$). The difference attributable to the device ($\$0.60$) is about three times smaller than the difference attributable to the promise ($\approx \$2.16$).

### 2.2 Belief Elicitation

First-order beliefs: $\tau_R(\mu, 1/6) = 0.24$ under the unreliable device; somewhat higher under the reliable device, but the difference was not significant when a promise was made ($p = 0.15$). This confirms that the reliability device shifts second-order beliefs while leaving first-order beliefs approximately unchanged.

Second-order beliefs: $0.64$ under the reliable device versus $0.53$ under the unreliable device when a promise was made ($p < 0.01$). This is the variation the model predicts should drive performance.

### 2.3 Opt-Out Behavior

Opt-out rates were $7.3\%$ (promise), $12.8\%$ (empty talk), and $21.6\%$ (no message), confirming that promises credibly signal higher promisor generosity to receivers.

---

## 3. Theoretical Framework: Conditional Guilt Aversion

### 3.1 Model

The dictator's utility is

$$U_D(a) = \pi_D(a) - \frac{\mu \gamma_D}{k}\left(\max\left\{E[\pi_R \mid \tau_D, \rho] - \pi_R(a), 0\right\}\right)^k,$$

where $\mu \in \{0,1\}$ is an indicator for whether a promise was made, $\gamma_D \geq 0$ is the guilt aversion coefficient, $\tau_D(\mu, \rho)$ is A's second-order belief (belief about B's expectation of A's contribution), and $k > 1$ governs the convexity of guilt. With payoffs $\pi_D = 14 - 4a$ and $\pi_R = 12a$, the expected payoff to B conditional on A's second-order beliefs is $E[\pi_R \mid \tau_D, \rho] = 12\rho\tau_D(\mu, \rho)$, giving:

$$U_D(a) = 14 - 4a - \frac{\mu \gamma_D \cdot 12^k}{k}\left(\max\left\{\rho\tau_D(\mu,\rho) - a, 0\right\}\right)^k.$$

**Conditional guilt**: guilt is activated ($\mu = 1$) only when a promise is made. Without a promise ($\mu = 0$) guilt does not enter regardless of $\gamma_D$.

For guilt-averse dictators ($\gamma_D > 0$, $\mu = 1$), the interior optimum is

$$a^* = \rho\tau_D - \left(\frac{4}{\gamma_D \cdot 12^k}\right)^{1/(k-1)}.$$

### 3.2 Testable Restriction

**TR1.** If a promise is made ($\mu = 1$), equilibrium contribution $a^*$ is higher under the reliable device ($\rho = 5/6$, higher $\tau_D$) than under the unreliable device ($\rho = 1/6$, lower $\tau_D$). Without a promise ($\mu = 0$), there is no difference across reliability conditions.

This is the central testable restriction, which the data confirm.

### 3.3 Distribution of Guilt Aversion

Structural estimation reveals that approximately $50\%$ of dictators have $\gamma_D > 0$ (guilt-averse). Of these, roughly $25\%$ have very high guilt aversion ($\gamma_D \approx 20$) and choose $a^* \approx \rho\tau_D$ to eliminate guilt entirely; the remaining $25\%$ have intermediate values.

---

## 4. Conclusion

This paper provides the first direct experimental evidence that second-order beliefs — promisors' beliefs about promisees' expectations — are the mechanism through which promises affect behavior. A conditional guilt aversion model, in which guilt is activated only when a promise is made, organizes the experimental results: higher second-order beliefs lead to higher performance when a promise is made, with no effect absent a promise. The findings establish that the binding force of a promise operates through the expectations it creates rather than through intrinsic commitment value or social norms alone.
