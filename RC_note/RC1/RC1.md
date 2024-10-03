# VE203 RC1

> In RC1, we will go over logic, proposition, boolean algebra, truth tree and natural deduction. There are important and must be tested in mid-term exam.

## Proposition

Basic and foundamental concept in this chapter. 

**Definition**: A proposition or statement is a declarative sentence that is either true or false, but not both.

As a result, the combination of quantifier and predicate forms a proposition.

## Connectives

$\land \   \text{,} \ \lor \text{,} \ \lnot \ \text{,} \to \ \text{,} \ \leftrightarrow $

Here **notation**, **priority** and **Truth Table** are very important, especially for $\to$.

## Connective Priority

If you don't remember these well, you may be lost when you see a complicated predicate.

$ ( \ \ \ ) > \neg > \land >  \lor > \ \to \ > \ \leftrightarrow $

---

## Simple Boolean Algebra

You don't have to master them, and you may not meet them in exams. But we have to mention them.

**Tautology**: all cases lead to 1.

**Contradiciton**: all cases lead to 0.

**Equivalence**: $p$ and $q$ are equivalent if $p \leftrightarrow q$ is a tautology. Denoted by $p \Leftrightarrow q$.

**Formal Implication**: We say that $p$ formally implies $q$ if $p \to q$ is a tautology, denoted by
$p \Rightarrow q$.

We use tautology equivalence (as shown in slides) to simplify and further to prove some unapparent equivalence.

Eg. $ p \to q \Leftrightarrow \neg q \to \neg p \Leftrightarrow \neg p \lor q$

---

## Truth Tree

Truth Tree used to be an important proof method. However, this won't be tested this semester. Basic process is as follows.

1. Use basic rule shown in slides; draw proposition into a tree
2. Do one operation for each step (don't do something like double negation and split or-proposition at the same time)
3. Write down condition, then negation of conclusion
4. Operate each proposition and degrade them into simple proposition (with only one letter)
5. If contradiction occurs in one branch, use $\times$ to show it is closed.

However, since we don't need to practice on that, **online proof generator** is more recommended. Please go to [www.umsu.de/trees](www.umsu.de/trees).

---

## Natural Deduction

This will be tested in exam. This can be hard in exam but you can try to get as many points as you can.

Basic process is as follows.
1. Observing the pattern of conclusion and guess what rule may be used for the last step.
2. Repeat step 1 to see whether you can make the whole tree (from the bottom to the top)
3. Make necessary assumption
4. Remember to use rule to discharge all assumption
5. If you find one way is false, please turn to another route

Easier said than done. More exercise is on worksheet.