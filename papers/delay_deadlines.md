# Delay and Deadlines: Freeriding and Information Revelation in Partnerships

**Arthur Campbell** (Yale University)
**Florian Ederer** (Boston University; CEPR, ECGI, and NBER)
**Johannes Spinnewijn** (London School of Economics; CEPR)

*American Economic Journal: Microeconomics*, Vol. 6, No. 2, pp. 163–204, May 2014

---

## Abstract

We study a partnership problem in which two agents must make a joint decision but can acquire private information before doing so. Each agent bears a cost to delay the decision and a cost to acquire information, and agents have an incentive to free-ride on their partner's information. We characterize the equilibrium and show that it features strategic concealment of information: an agent who has already acquired a signal prefers to delay revealing it, to keep the partner searching. We derive a deadline paradox: tighter deadlines can increase expected decision time and improve decision quality. We also show that, under optimally chosen deadlines, a regime with private information can dominate a regime with public information — a manifestation of Parkinson's Law.

**JEL Codes:** C72, D70, D82, D83.

---

## Model

### Environment

Two agents must make a binary joint decision. The payoff from the decision depends on an unknown state $\theta$.

- State: $\theta \sim N(0, 1/\varepsilon)$, with prior precision $\varepsilon$
- Each signal: $s \sim N(\theta, 1/\tau)$, with signal precision $\tau$
- Effort $e$ generates a signal at flow rate $\lambda e$, at flow cost $c$ per unit of effort
- The decision is irreversible and can be called by either agent at any time up to a deadline $T$

Expected loss from deciding with $n$ accumulated signals:

$$L_n = \frac{1}{\varepsilon + \tau n}$$

The marginal return to the $n$-th signal (reduction in expected loss):

$$\alpha_n = \frac{\tau}{(\varepsilon + \tau n)(\varepsilon + \tau(n+1))}$$

Agents share the decision payoff equally, so each receives half the expected reduction in loss from acquiring additional signals.

### Strategic Concealment

An agent who has acquired a signal prefers not to reveal it immediately. If the informed agent reveals the signal, the partner's effort drops because the partnership now has better information and less to gain from further search. By concealing the signal, the informed agent induces the partner to continue searching, increasing the probability that a second signal is found before the deadline.

This incentive for strategic concealment is the central friction in the model.

---

## Equilibrium

### Threshold Characterization

The equilibrium is characterized by two time thresholds, $X$ and $Y$:

- **Threshold $X$:** The time at which, under maximum effort, the posterior belief that a first signal has been found (by either agent) reaches the critical level $\bar{\phi}$ — the belief at which the return to further delay equals the cost.
- **Threshold $Y$:** Defined by $\delta Y = (1 - \bar{\phi}) \alpha_2$, where $\delta$ is the delay cost per unit time. $Y$ is the deadline length at which the expected value of a second signal (conditional on no signal yet found) exactly justifies the cost of an additional unit of delay.

### Proposition 1: Three Equilibrium Regimes

Equilibrium behavior depends on the deadline $T$ relative to the thresholds $X$ and $Y$:

**Short deadline ($T \leq X$):** Both agents exert maximum effort throughout. All acquired information is concealed until the deadline, and the decision is made at time $T$. The deadline is binding and effort is at its highest.

**Intermediate deadline ($X < T \leq Y$):** Agents exert maximum effort until time $T - X$, then switch to zero effort. A signal acquired early is revealed at the deadline, not immediately. The equilibrium features a phase of high effort followed by a phase of inactivity, with information revealed only at the end.

**Long deadline ($T > Y$):** There is an initial phase of information disclosure (low effort, signals revealed immediately as found) followed by a phase of concealment and high effort. In the initial phase, agents reveal signals as they are found because the deadline is far enough away that concealment is not profitable. Once the belief that only one signal has been found reaches a critical threshold, agents switch to concealment and high effort.

---

## The Deadline Paradox

A central result of the model is that **tighter deadlines can increase both expected decision time and decision quality**.

The intuition is as follows. Under a long deadline, agents spend significant time in the disclosure phase with low effort, making the partnership inefficient. A tighter deadline eliminates or shortens the disclosure phase, inducing maximum effort throughout. The increase in effort under the tighter deadline can raise the probability that signals are found before the deadline, so the expected time until a decision is reached (conditional on one being made) increases even as the deadline shortens. The quality of the decision also improves because more information is gathered under higher effort.

This paradox holds in an intermediate range of deadlines where shortening the deadline shifts the equilibrium from the long-deadline regime to the intermediate or short-deadline regime.

---

## Parkinson's Law: Private vs. Public Information

The model compares two institutional arrangements:

- **Private information:** Agents observe only their own signals; the partner's signals are not observable.
- **Public information:** All signals are immediately observable by both agents.

Under public information, there is no concealment, but the free-rider problem is more severe: once a signal is publicly observed, each agent has less incentive to search further, knowing the partner will also reduce effort.

**Result.** Under optimally chosen deadlines, **welfare is strictly higher under private information** than under public information. This is a manifestation of **Parkinson's Law** — work expands to fill the time available. Under private information with an optimally chosen deadline, the concealment incentive is harnessed: agents continue to search even after a signal has been found because they do not observe the partner's discovery. This results in higher average effort and more information gathered before the decision.

Under public information, the deadline cannot harness concealment because signals are immediately revealed. The free-rider problem under public disclosure cannot be overcome by deadline design alone.

---

## Extensions

### Communication Frictions

When agents can communicate imperfectly (with noise or delay), the qualitative results are preserved. Communication frictions effectively make the regime closer to private information, which can improve welfare if optimally managed.

### Committee Chairperson

Introducing an asymmetric decision rule — where a chairperson has the right to call the decision unilaterally — changes the equilibrium. The chairperson internalizes more of the decision benefit and exerts higher effort than symmetric partners. This can improve or worsen outcomes depending on the information structure.

### Additional Team Members

Adding agents to the partnership increases the free-rider problem and the concealment incentive. The paradox and Parkinson's Law results extend to teams of arbitrary size, though the optimal deadline and effort levels depend on team composition.

---

## Conclusion

In partnerships with joint decisions and private information acquisition, strategic concealment of information is an equilibrium outcome: informed agents delay revelation to induce continued partner search. This generates a deadline paradox — tighter deadlines can increase expected decision time and improve decision quality by eliminating unproductive disclosure phases and sustaining high effort. Under optimally set deadlines, private information regimes dominate public information regimes, because the concealment incentive can be harnessed to sustain effort in a way that the free-rider problem under public information cannot. These results have implications for the design of committee rules, the governance of partnerships, and the interpretation of procrastination and delay in organizations.
