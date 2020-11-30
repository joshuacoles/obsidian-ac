Let $(X, d)$ be a [[Metric]], $F \subseteq X$.

$$
F \sim \text{closed} \iff X \backslash F \sim \text{open}
$$

## Proof ($\implies$)

- Suppose $F$ is closed.
- Let $x \in X \backslash F$.

Since:
- $x \notin F \land x \notin F$
- $x$ is not a [[cluster point]] of $F$.

Thus,

$$
\neg \left[ \forall r > 0 : (B_r(x) \backslash \{x\}) \cap F \neq \emptyset \right]
$$

or equivalently,

$$
\exists r > 0 : (B_r(x) \compl \{x\}) \cap F = \emptyset.
$$

Since,

$$
\begin{alignat}{3}
&& (x-1)^2 &= -1      && \phantom{\implies} 

\\ 
\implies &&     x-1 &= \pm i   && \\ \implies &&       x &= 1 \pm i &&
\end{alignat}
$$

Since $x \notin F$,
