# VE203 RC2

> In RC2, we will review induction, including weak induction, strong induction, string, structural induction, some algebra knowledge, including monoid and monoid homomorphism, and equinumerosity. Induction is close to our intuition so it may not be that abstract but equinumerosity is tough so you should grasp the definition very well. Besides, relation will be discussed later since this part is close to partial order.

## Basic Structure

Induction is a rather powerful tool in proof. The core philosophy is that some things are not constructed randomly but elaborately-designed. Therefore, we can find inner pattern. Everything starts from the simplest situation, which is **base case**.

$(1) \ \text{base case: P(0) is correct}$

Then, things get more complicated (for natural number, number is getting bigger; string may get longer), so we have **inductive case**.

$(2) \ \text{inductive case: } \forall \ n \in \N, (\text{P(n)} \to \text{P(n+1)})$

What's important that in **inductive case**, $\text{P(n)}$ is the **Inductive Hypothesis**.

Therefore, the basic structure of induction is 
1. **Base Case**, 
2. **Inudctive Hypothesis**, 
3. **Inductive Case**

---

## Different Form of Induction

- Another form of normal induction
    1. All of $\text{P(0)}$, $\text{P(1)}$, $...$ , $\text{P(k−1)}$ are true.
    2. ($\forall \text{n}$)($\text{P(n)} \to \text{P(n+k)}$)
- Strong Induction
    1. $\text{P(0)}$
    2. ($\forall$ n $\geq$ 1), [$\text{P(0)} \land \text{P(1)} \land \text{P(2)} ... \land \text{P(n - 1)} \to \text{P(n)}$].
- Structural Induction
    1. From my point of view, I would like to say both induction follow the same philosophy (the construction of something like string and natural number follows a pattern), but they use different characteristic of that pattern.
    2. For natural number, we have addition (2 = 1+1). Therefore, we can use mathematical induction. This is a kind of `mathematical characteristic` of natural number. We can also perform structural induction since there is successor (will be discussed later; 2 is the successor of 1). This is kind of `structure characteristic` of natural number.
---

## An interesting topic: String

Before we jump into this topic, we should talk about algebraic basics.

### Monoid

**Definition**: A monoid is a triple $(M, e, \cdot)$, where $M$ is a set, together with an identity element $e$, and a function $M \times M \to M$, such that for all $m,n,p \in M$, the following monoid laws hold,
- $ m \cdot e = e \cdot m = m $ 
- $(m \cdot n) \cdot p = m \cdot (n \cdot p)$

Here follows a question: How to prove a monoid?
**Step 1.** Check identity element exists
**Step 2.** Check identity element is unique
**Step 3.** Check associativity

### Monoid Homorphism

**Definition**: A monoid homomorphism, or monoid morphisms, between two monoids $(M, *, e_M)$ and $(N, \cdot, e_N)$ is a function $f : M \to N$ such that
- $f (x * y) = f(x) \cdot f(y)$ for all $x, y \in M$, and
- $f (e_M) = e_N$.

Again! How to check?
**Only Step**: Follow the rules!!!!