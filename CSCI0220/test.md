-   [Statements, Proofs, and
    Contradiction](#statements-proofs-and-contradiction)
    -   [Propositions](#propositions)
    -   [Notation](#notation)
    -   [Who decides truth?](#who-decides-truth)
    -   [What is a predicate?](#what-is-a-predicate)

# Statements, Proofs, and Contradiction

## Propositions

What is a proposition? Definition: A proposition is a statement that is
either **true** or **false**

    - Proposition 1: 2 + 3 = 5
    - Proposition 2: 1 + 1 = 3
    - Proposition 3: The sum of any two odd numbers is even
    - Proposition 4: The product of any two odd numbers is even

How do we tell if a proposition is true?

We can give an example:

-   Proposition 5: There is a two-digit perfect square whose final digit
    is 4.
    -   True. 8<sup>2</sup> = 64
-   Proposition 6: There is a two-digit perfect square whose final digit
    is 8.
    -   False. We can enumerate and see there is no possible answer
-   Proposition 7: There is a perfect square whose final digit is 4.
    -   True. we showed it earlier
-   Proposition 8: There is a perfect square whose final digit is 8
    -   False.

Proposition 9: For every nonnegative integer, n. the value of
*n*<sup>2</sup> + *n* + 41 is prime

Proof by counter example:

Define *p*(*n*) :  := *n*<sup>2</sup> + *n* + 41

*p*(0) = 41

⋮

*p*(10) = 151

## Notation

-   ℤ is the **integers**
-   ℤ<sup>+</sup> is **positive integers**
-   ℕ is the **non-negative integers**
-   ∀ means **for all**
-   ∃ means **there exists**

Examples:

∀*n* ∈ ℕ, *n*<sup>2</sup> mod 10 = 6

Proposition 10: Euler’s conjecture

∀*a*, *b*, *c*, *d* ∈ ℤ<sup>+</sup>, *a*<sup>4</sup> + *b*<sup>4</sup> + *c*<sup>4</sup> ≠ *d*<sup>4</sup>

No!

## Who decides truth?

-   The goal of mathematics is “common knowledge”: give anyone the
    definitions, and a proof or counterexample, and they can check it.
    Even a computer could do it.
-   This is why we focus on *mathematical* propositions here.

## What is a predicate?

A *predicate* is a proposition whose truth depends on the value of one
or more variables.

Examples: - *n* is odd - The sum of consecutive numbers *a* and *b* is
prime - *x* is an integer, 2*x* is even

Use quantifiers to turn predicates into propositions

Predicate notation:

``` math
\begin{align}
    p(n)
\end{align}
```
