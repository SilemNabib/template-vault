## Concept Overview

Three basic components in **probability models**
- The set of all possible outcomes, denoted $\Omega$.
- The collection of all sets of outcomes (events), denoted $A$ 
- And a probability measure $\mathbb{P}$ assigns a probability to each event.

> The following examples are based on the case of flipping a coin in the air.

##### Sample space (Ω)
$$\Omega = \{ \text{Heads}, \text{Tails} \}$$

##### Event Collection (A)
$$A = \{ \emptyset, \{ \text{Heads} \}, \{ \text{Tails} \},\{ \text{Heads}, \text{Tails} \} \}$$

##### Probability Measure (P)
$$\mathbb{P}(\text{Heads}) = 0.5 \:\:\:\:\:\:\:\: \mathbb{P}(\text{Tails}) = 0.5$$

**How do we assign a probability to an event?**
![[Pasted image 20241024075431.png]]

## Joint Probability $P(A \bigcap B)$

The expression $P(A ∩ B)$ or equivalently $P(A, B)$ stands for the probability of the events $A ∩ B$. represents the joint probability of two events A and B occurring at the same time.

## Conditional Probability $P(A | B)$

The probability of an event given that another event has occurred. It can be calculated using the formula: $P(A|B) = P(A ∩ B) / P(B).$

**Ex.** If there are 10 balls ($7$ red, $3$ blue), the probability of drawing a red ball after drawing a blue one is $P(\text{Red } | \text{ Blue}) = \frac{7}{10}$.

## Bayes' Theorem
Probability review What is the Bayes’ Theorem? Bayes’Theorem gives a mathematical rule for inverting conditional probabilities, allowing us to find the probability of a cause given its effect.

- Having $P(A|B) = \frac{P(A \bigcap B)}{P(B)}$
- Having $P(B|A) = \frac{P(B \bigcap A)}{P(A)}$
- By solving both equations for $P(A \bigcap B)$ and equating them we obtain Bayes’ theorem

$$P(B|A) = \frac{P(B \bigcap A) \cdot P(A)}{P(B)}$$


## Independence of Events
When do we call two events independent?

- Two events $A$ and $B$ are said to be independent if $P(A|B) = P(A)$. 
- In other words, $B$ provides no information about whether $A$ has occurred. 
- $P(A ∩ B) = P(A) · P(B)$


## Marginalization
![[Pasted image 20241024114559.png]]