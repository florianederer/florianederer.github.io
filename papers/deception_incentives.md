# Deception and Incentives: How Dishonesty Undermines Effort Provision

**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Ernst Fehr** (University of Zürich)

*Working Paper* — Revise & Resubmit: *Management Science*

---

## Abstract

In this paper we show that subtle forms of deceit undermine the effectiveness of incentives. We design an experiment in which the principal has an interest in underreporting the true performance difference between the agents in a dynamic tournament. According to the standard approach, rational agents should completely disregard the performance feedback of self-interested principals and choose their effort level as if they had not been given any information. However, despite substantial underreporting many principals seem to exhibit lying aversion which renders their feedback informative. Therefore, the agents respond to the feedback but discount it strongly by reducing their effort relative to fully truthful performance feedback. Moreover, previous experiences of being deceived exacerbate the problem and eventually reduce average effort even below the level that prevails in the absence of any feedback. Thus, both no feedback and truthful feedback are better for incentives than biased feedback.

**Keywords:** Deception, Dishonesty, Communication, Cheap Talk, Dynamic Tournaments.
**JEL Codes:** D83, C92, M12.

---

## Theoretical Framework

### A Simple Model of Dynamic Tournaments

The paper models a tournament for a fixed prize between two risk-neutral agents $i = A, B$ over 2 stages, $t = 1, 2$. Agent $i$'s output in stage $t$ is $x_t^i = e_t^i + \varepsilon_t^i$, where $e_t^i$ is the privately chosen effort level and $\varepsilon_t^i$ is a noise term. Agent $A$ wins if $x_1^A + x_2^A > x_1^B + x_2^B$. The noise difference $\varepsilon_t^A - \varepsilon_t^B \sim N(0, \sigma^2)$ and the sum of noise differences $\sim N(0, 2\sigma^2)$.

Agent $i$'s payoff is:
$$U^i = p + (P-p)\Pr(x_1^i + x_2^i > x_1^j + x_2^j) - c(e_1^i) - c(e_2^i).$$

Three settings are compared:
- **No Feedback (NF):** Neither agent knows the first-stage output difference $\Delta \equiv x_1^A - x_1^B$ when choosing second-stage effort.
- **Truthful Feedback (TF):** The first-stage output difference $\Delta$ is truthfully revealed to both agents before second-stage effort choices.
- **Principal Feedback (PF):** A self-interested principal observes $\Delta$ and sends a private non-verifiable message $\hat{\Delta}^i$ to each agent.

### Equilibrium Analysis

**Without Feedback (NF):** The unique symmetric Nash equilibrium requires $c'(e^{NF}) = (P-p)g(0)$, where $g(\cdot)$ is the density of the sum of noise differences. For normally distributed noise with quadratic costs: $c'(e^{NF}) = (P-p)/(2\sigma\sqrt{\pi})$.

**With Truthful Feedback (TF):** Second-stage effort satisfies $c'(e_2^{TF}) = (P-p)f(\Delta)$, where $f(\cdot)$ is the normal density of the stage-2 noise difference. Effort is highest when $\Delta = 0$ (neck-and-neck competition) and decreasing in $|\Delta|$. First-stage effort equals first-stage effort under NF: $c'(e_1^{TF}) = (P-p)g(0)$.

**With Principal Feedback (PF):** A risk-neutral self-interested principal has payoff $U^P = \theta(x_1^A + x_2^A + x_1^B + x_2^B) - P - p$, giving the principal an incentive to underreport $\Delta$ to increase agent effort. However, the unique Perfect Bayesian Equilibrium is a **babbling equilibrium**: all messages are uninformative because for any belief agents hold, the optimal message for the principal is $\hat{\Delta}^i = 0$. Hence all communication is uninformative and agents should behave as in the NF setting.

**Key prediction (Cheap Talk Hypothesis):** If agents are rational, effort under PF should equal effort under NF. Thus no information and fully truthful information are superior to feedback by self-interested principals.

---

## Experiment Design

### Three Treatment Conditions

The experiment was designed to test the predictions of the model with exogenous variation in the credibility of information.

**NF treatment:** No principal; contestants received no information about first-stage outcomes before the second stage.

**TF treatment:** No principal; the experimenter exogenously enforced truthful feedback about the first-stage output difference, provided privately to each contestant.

**PF treatment:** Principals observed first-stage outcomes and sent non-verifiable private messages about output levels and the output difference to each agent. Principals were free to report any output level irrespective of actual outcomes. Agents knew this. Principals were required to send some message (no option to remain silent).

**Parameters:** The set of feasible effort levels was $e \in \{1, 2, \ldots, 100\}$. Parameters were chosen so the equilibrium effort $e^{NF} = 37$ in both stages. 192 subjects participated in 16 sessions of 12 subjects each (16 matching groups as independent units). Sessions lasted 75 minutes on average. Subjects were science students at the University of Zurich and ETH Zurich. Average earnings: CHF 43.40 (≈$36).

---

## Results

### The Feedback Hypothesis

The effort response to feedback in the TF condition confirms the model's prediction: **second-stage effort is decreasing in the absolute magnitude of $|\Delta|$**. When the gap between contestants is large, incentives to compete are low; when contestants are neck-and-neck ($\Delta \approx 0$), second-stage effort is highest.

### Agents Respond to Biased Feedback

Contrary to the cheap talk prediction, principals' messages in the PF treatment were **partially informative** — they were not mere babbling. Some principals provided truthful feedback while others consistently reported much smaller output differences. On average, a one-unit increase in reported output difference was associated with a true increase of approximately two units. It was therefore rational for agents to respond to variations in the reported output differences.

**Consequence:** Agents in the PF treatment respond to feedback more strongly than to truthfully reported differences of the same magnitude in the TF treatment, because a reported difference of $\Delta$ in PF is on average a signal of a true difference of $2\Delta$. As a result, agents strongly discount the message: average effort after feedback in PF is eventually **lower than in TF and even lower than in NF**.

### Deceit Has Persistent Effects

The negative effect of deceitful messages on effort was not limited to the post-feedback stage. Over time, agents' average effort in the PF condition declines even in the **pre-feedback** stage. This indicates a pervasive negative effect of deceit on overall effort levels. Agents who faced higher frequencies of underreported output differences in past interactions were significantly more likely to choose low effort even before receiving feedback.

This finding captures an important effect: even a rational agent's first-stage effort should not be affected by the expectation that the principal will send false feedback about the first-stage outcome. The reduction in pre-feedback effort therefore reflects a broader undermining of incentives through prior deception.

### A Non-Monotone Effect of Feedback

The experiment documents a striking non-monotone effect of feedback information on tournament incentives:
- **No feedback (NF):** Moderate effort.
- **Truthful feedback (TF):** Higher effort when $|\Delta|$ is small; lower when $|\Delta|$ is large; similar on average.
- **Principal feedback (PF):** Average effort falls below NF due to strong discounting of partially informative messages.

Thus, no information or completely uninformative feedback and fully truthful information are **both better** than partially informative feedback from a self-interested principal.

### Lying Aversion Explains the Evidence

A model of heterogeneous lying aversion explains the key features of the data:
- Some principals have high psychic costs of lying and provide truthful feedback even when biasing would be profitable.
- Agents rationally infer that messages are partially informative and respond accordingly.
- Strongly Machiavellian subjects (high selfishness and opportunism on the Machiavelli scale) lie significantly more.
- Agents who have been deceived more often update upward the probability they face a deceitful principal, discount feedback more strongly, and provide lower effort.

The partial informativeness of messages — and agents' subsequent effort response that is too strong relative to the true signal — is the central mechanism generating lower average effort in PF than in TF and NF.

---

## Conclusion

Biased performance appraisals can thoroughly undermine incentives even when principals cannot manipulate the payments themselves (agents are correctly paid according to their output performance). The experiment shows that even quite subtle forms of deceit — underreporting performance differences rather than withholding pay — significantly reduce effort.

The results suggest that in many organizational settings, it might be better to provide no performance feedback than to allow managers the discretion to bias it. This finding may help explain the empirical observation that performance feedback in organizations is often quite uninformative.
