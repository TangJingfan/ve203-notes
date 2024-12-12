# VE203 RC6

> Congrats! We finally reach the end of the semester. This is the final recitation class and I will provide a checklist for you.

## Linear Recurrence Relation

- How to solve a linear Recurrence Relation?
    - Please use Formal Power Series and Generating Function.
    - Properly set Formal Power Series.
    - Use partial fraction to make calculation easier.

e.g

Given the recurrence relation:  

\[
a_{n+2} - 4a_{n+1} + 3a_n = n2^n, \quad n \geq 0
\]

with \( a_0 = 1 \), \( a_1 = 2 \).  
We have  

\[
\sum_{n \geq 0} \left( a_{n+2} - 4a_{n+1} + 3a_n \right)x^n = \sum_{n \geq 0} n2^n x^n
\]

Let \( A(x) = \sum_{n \geq 0} a_n x^n \), then  

\[
\frac{A(x) - 1 - 2x}{x^2} - 4 \frac{A(x) - 1}{x} + 3A(x) = \frac{2x}{(1 - 2x)^2}
\]


## Formal Power Series

- How to perform calculation?
    - Review slides.
    - Do remember those properties well.

e.g

![alt text](fps_add.png)

![alt text](fps_multi.png)

![alt text](fps_comp.png)

![alt text](fps_deri.png)

- How to find inverse power series?
    - \(a_0 \neq 0\)
    - Use geometric series. 

## Binomial Theorem

- Why we learn Binomial Theorem?
    - When we use formal power series to solve counting problems, we intend to find the coefficient of certain terms. Binomial Theorem helps us to find those terms.

- What should we remember?
    - Four identities.
    - Definition of \(\binom{m}{k}\).

- \[
(1 + x)^{-d} = \sum_{n \geq 0} \binom{-d}{n} x^n = \sum_{n \geq 0} (-1)^n \binom{d + n - 1}{n} x^n
\]

- \[
(1 - x)^{-d} = \sum_{n \geq 0} \binom{-d}{n} (-x)^n = \sum_{n \geq 0} \binom{d + n - 1}{n} x^n
\]

- \[
(1 + x)^n = \sum_{k \geq 0} \binom{n}{k} x^k = \sum_{k=0}^n \binom{n}{k} x^k \quad \text{if } n \in \mathbb{N}
\]

- \[
\frac{x^k}{(1 - x)^{k+1}} = \sum_{n \geq 0} \binom{n}{k} x^n = \sum_{n \geq k} \binom{n}{k} x^n
\]

## Principle of Inclusion-Exclusion

- What is PIE?

- How to use PIE in counting problems?
    - Derangement.
    - Counting Surjection.

## Asymptotic Notations

- What do different symbols mean?
    - Big O
    - Omega
    - Theta

## Master Theorem

- How to use Master Theorem?
    - First judge the relationship between coefficients. 
    - Then choose appropriate formula.

![alt text](mas_thm.png)

## Number Theory

- How to show there exist infinitely many primes which are of certain term?
    - Use Euclid’s proof to construct a set.

![alt text](proof_euclid.png)

- How to perform Euclidean algorithm?
    - Follow the step.

![alt text](eucl_algo.png)

- How to find integer solutions for a Diophantine equation?
    - Use Euclidean algorithm by back-tracking.
    - Some time, there will exist no integer solution for a diophantine equation. For a equation \(ax + by = c\), if \(gcd(a,b) \nmid c, no integer solution.\)

![alt text](diop_equ.png)

- How to find inverse?

- How to solve Sunzi Problem?

- How to calculate RSA?

## Group Theory

- What is a group?

![alt text](group.png)

- What is a subgroup? 
    - A subgroup is a subset of a group that is itself a group under the same operation as the original group.

- What is a cyclic group?

- What is symmetric group?

- What is coset?

- What is Lagrange Theorem?

- What is normal subgroup?

## Graph Theory

- What is a graph?

- What is complete?

- What is subgraph?

- What is connectivity?

- What is bipartition?

- What is matching?

- What is a tree?

- What is a spanning tree?

- How to apply Kruskal’s Algorithm?

- How to apply Dijkstra’s Algorithm?