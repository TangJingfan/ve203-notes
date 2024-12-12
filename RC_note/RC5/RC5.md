# VE203 RC5

> I am sorry that number theory is also a new friend of me, therefore my recitation class would cover almost everything regarding the slides. You are highly welcomed to come to RC or OH to discussion number theory with us!

## Divisibility

**Definition:** Let \( n, d \in \mathbb{Z} \) with \( d \neq 0 \). We say that \( d \) divides \( n \), denoted by \( d \mid n \), if \( n = dk \), for some \( k \in \mathbb{Z} \), i.e.,

\[
d \mid n \iff (\exists k \in \mathbb{Z})(n = dk)
\]

By convention, \( 0 \mid n \) only if \( n = 0 \).

### Equivalent Statements

- \( d \) divides \( n \).
- \( n \) is divisible by \( d \).
- \( n \) is a multiple of \( d \).
- \( d \) is a divisor of \( n \).
- \( d \) is a factor of \( n \).

## Non-divisibility

If \( d \) does not divide \( n \), we write \( d \nmid n \). In other words:

\[
d \nmid n \iff \frac{n}{d} \notin \mathbb{Z}
\]

### Examples

1. \( n \mid 0 \) for all \( n \in \mathbb{Z} \).
2. \( 1 \mid n \) for all \( n \in \mathbb{Z} \).
3. If \( d \in \mathbb{Z} \), then \( d \mid 1 \implies d = \pm 1 \).

---

## Prime Number

**Definition:** A natural number \( p \in \mathbb{N} \) is a **prime number** (or simply, a **prime**) if \( p \geq 2 \) and if \( p \) is divisible only by itself and 1.


## Remark

A natural number \( p \in \mathbb{N} \) is a prime number if it has **exactly two distinct factors**.  
The set of all primes is sometimes denoted by \( \mathbb{P} \).


## Additional Notes

- **1 is NOT a prime number.**

## Theorem

There are infinitely many primes.

### Proof (Proof of Euclid.)

I will lead you to prove.

### Lemma

Given \( p \in \mathbb{P} \) (a prime number) and \( n \in \mathbb{N} \), if \( p \mid (n^2 + 1) \), then:

- \( p = 2 \), or  
- \( p \) is of the form \( 4m + 1 \), where \( m \in \mathbb{Z} \).

---

## Euclidean Algorithm

### Input:
\( m, n \in \mathbb{N} \setminus \{0\}, m \leq n \)

### Output:
Greatest common divisor of \( m \) and \( n \)

### Algorithm:
1. **Function** \( \text{gcd}(m, n) \):
2. &emsp; **if** \( n \bmod m = 0 \) **then**
3. &emsp;&emsp; **return** \( m \)
4. &emsp; **else**
5. &emsp;&emsp; **return** \( \text{gcd}(n \bmod m, m) \)
6. **end**
7. **end**

**notes:** I thinks it is more like a matter of method. Once you master it, it is not so difficult.

---

## Least Common Multiple

### Theorem
Let \( a, b \in \mathbb{Z} \setminus \{0\} \), and let \( m = \text{lcm}(a, b) \) be their least common multiple — the positive integer that generates the subgroup \( S = a\mathbb{Z} \cap b\mathbb{Z} \), i.e.,

\[
m\mathbb{Z} = a\mathbb{Z} \cap b\mathbb{Z}.
\]

### Properties
1. \( a \mid m \) and \( b \mid m \).
2. If \( a, b \mid n \) for some \( n \in \mathbb{Z} \), then \( m \mid n \).
