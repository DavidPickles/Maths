# Theorems, Definitions, and Postulates

Mathematical Statistics (4th Ed) by John E. Freund and Ronald E. Walpole (Prentice-Hall 1987)
    
## Postulates 

These apply to a discrete sample space $S$ which is a set of mutually exclusive outcomes. Events are subsets of $S$.

### Postulate 1

The probability of an event is a non-negative real number; that is, $P(A) \geqslant 0$ for any subset $A$ of $S$.

### Postulate 2

$P(S) = 1$

### Postulate 3

If $A_{1},A_{2},A_{3},\ldots,$ is a finite or infinite series of mutually exclusive events of $S$, then

$P(A_{1} \cup A_{2} \cup A_{3} \cup \cdots) = P(A_{1}) + P(A_{2}) + P(A_{3}) + \cdots$

## Theorems and Definitions

### Theorem 2.1

If $A$ is an event in a discrete sample space $S$, then $P(A)$ equals the sum of the probabilities of the individual outcomes comprising $A$. 

### Theorem 2.2

If an experiment can result in any one of N different equally likely outcomes, and if n of these outcomes together constitute event A, the the probability of event A is 

$$
P(A) = \dfrac{n}{N}
$$

### Theorem 2.3

If $A$ and $A'$ are complementary events in a sample space $S$, then

$$
P(A') = 1 - P(A)
$$

### Theorem 2.4

$P(\emptyset) = 0$ for any sample space $S$.

### Theorem 2.5

If $A$ and $B$ are events in a sample space $S$ and $A \subset B$, then $P(A) \leqslant P(B)$.

### Theorem 2.6

$0 \leqslant P(A) \leqslant 1$ for any event $A$

### Theorem 2.7

If A and B are any two events in a sample space S, then 

$P(A \cup B) = P(A) + P(B) - P(A \cap B)$

### Theorem 2.8

If $A$, $B$, and $C$ are any three events in a sample space $S$, then

$P(A \cup B \cup C) = P(A) + P(B) + P(C) - P(A \cap B) - P(A \cap C) - P(B \cap C) + P(A \cap B \cap C)$

### Definition 2.1

If $A$ and $B$ are any two events in a sample space $S$ and $P(A) \ne 0$, the **conditional probability** of B given A is

$$
P(B|A) = \frac{P(A \cap B)}{P(A)}
$$

### Theorem 2.9

If $A$ and $B$ are any two events in a sample space $S$ and $P(A) \ne 0$, then

$$
P(A \cap B) = P(A) \cdot P(B|A)
$$

### Theorem 2.10

If $A$, $B$, and $C$ are any three events in a sample space $S$, such that $P(A) \ne 0$ and $P(A \cap B) \ne 0$, then

$$
P(A \cap B \cap C) = P(A) \cdot P(B|A) \cdot P(C|A \cap B)
$$

### Definition 2.2

Two events $A$ and $B$ are **independent** if and only if 

$$
P(A \cap B) = P(A) \cdot P(B)
$$

### Theorem 2.11

If any two events $A$ and $B$ are independent, then the two events $A$ and $B'$ are also independent.

### Definition 2.3

Event $A_1, A_2, \ldots,$ and $A_k$ are **independent** if and only if the probability of the intersection of any $2,3,\ldots$, or $k$ of these events equals the product of their respective probabilities.


### Theorem 2.12

If the events $B_1$, $B_2$, $\ldots$, and $B_k$ constitute a partition of the sample space $S$, and $P(B_i) \ne 0$ for $i=1,2,\ldots k,$ then for any event $A$ in $S$ 

$$
P(A) = \displaystyle\sum_{i=1}^k P(B_i) \cdot P(A|B_i)
$$

### Theorem 2.13

If the events $B_1$, $B_2$, $\ldots$, and $B_k$ constitute a partition of the sample space $S$, and $P(B_i) \ne 0$ for $i=1,2,\ldots k,$ then for any event $A$ in $S$ such that $A \ne 0$

$$
P(B_r|A) = \frac{P(B_r) \cdot P(A|B_r)}{\displaystyle\sum_{i=1}^k P(B_i) \cdot P(A|B_i)}
$$

for r = $1,2, \ldots, k$