# Birthday-Paradox

In a group of $n$ persons, what is the chance that some two have the same birthday? Assume birthday of a person is uniformly distributed in $\{1,2,\ldots,365\}$ and is independent of all other birthdays. Most people will think that you need at least 100 persons before you start seeing same birthdays. However, surprisingly perhaps, even with 23 persons there is a 50% chance of two sharing a birthday.

Event $A$: some two have same birthday

Event $A^c$: no two have same birthday

$A^c$: (Birthday 1 on any date $B_1$) and (Birthday 2 on any date other than $B_1$) and (Birthday 3 on any date other than $B_1$, $B_2$) and ... and (Birthday $n$ on any day other than $B_1,B_2,\ldots,B_{n-1}$)

$P(A^c)= 1 \cdot \left(1 - \frac{1}{365}\right)\left(1 - \frac{2}{365}\right)\cdots\left(1 - \frac{n-1}{365}\right)$

If $n=10$, what is the chance? If $n=30$, what is the chance?

We will do a Monte Carlo simulation to estimate the probability and compare with the calculation above.
