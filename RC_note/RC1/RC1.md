# VE203 RC1

> In RC1, we will go over logic, proposition, boolean algebra, truth tree and natural deduction. There are important and must be tested in mid-term exam.

## Proposition

Basic and foundamental concept in this chapter. 

**Definition**: A proposition or statement is a declarative sentence that is either true or false, but not both.

As a result, the combination of quantifier and predicate forms a proposition.

**Convention**: we use $1$ and $\top$ to represent true and use $0$ and $\perp$ to represent wrong.

## Connectives

$\land \   \text{,} \ \lor \text{,} \ \lnot \ \text{,} \to \ \text{,} \ \leftrightarrow $

Here **notation**, **priority** and **Truth Table** are very important, especially for $\to$.

## Connective Priority

If you don't remember these well, you may be lost when you see a complicated predicate.

$ ( \ \ \ ) > \neg > \land >  \lor > \ \to \ > \ \leftrightarrow $

## Logical Quantifiers

There are two types of quantifiers
- the universal quantifier, denoted by $\forall$
- the existential quantifier, denoted by $\exists$

## Predicate

**Definition**: A predicate is a function $ P:X\to \{\top, \perp \} $ with domain X.

Therefore, we can conclude that a quantifier plus predicate is a proposition.

Eg. $P(a): \exist \, a \in \R, a^3 >10.$ First half is quantifier and second half is predicate. Without quantifier, we cannot tell whether $P(a)$ is true or false. Quantifier is the domain of predicate.

## Nesting Quantifier

In a proposition, there may exist more than one $\forall$ or $\exist$. Their order matters.
- If same quantifiers, we can switch order. $\exists x, \exists y \Leftrightarrow \exists y, \exists x$
- If not, we can not switch them. $\exists x, \forall y \nLeftrightarrow \forall y, \exists X$

## Vacuous Truth

If the quantifier is alwasy false, the whole proposition is automatically correct.

Eg. Pink elephant can fly. This is correct because there is no pink elephant. ($\exists \  
\text{pink elephant, they can fly}$).

---

## Simple Boolean Algebra

You don't have to master them, and you may not meet them in exams. But we have to mention them.

**Tautology**: all cases lead to 1.

**Contradiciton**: all cases lead to 0.

**Equivalence**: $p$ and $q$ are equivalent if $p \leftrightarrow q$ is a tautology. Denoted by $p \Leftrightarrow q$.

**Formal Implication**: We say that $p$ formally implies $q$ if $p \to q$ is a tautology, denoted by $p \Rightarrow q$.

We use tautology equivalence (as shown in slides) to simplify and further to prove some unapparent equivalence.

Two things needed to be mentioned here is `proof by contrapositive` and `proof by contradiction`
- `proof by contrapositive`: $p \to q \Leftrightarrow (\neg \, q \to \neg \, p)$
- `proof by contradiction`: $ p \to q \Leftrightarrow \neg (p\, \land \neg \,q) \Leftrightarrow \neg p \lor q$


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
1. Observing the pattern of conclusion and guess what rule may be used for the last step. (For example, negation should be introduced; $\lor$ is the core connective so it should be introduced or a negation should be cancelled at last)
2. Repeat step 1 to see whether you can make the whole tree (from the bottom to the top)
3. Make necessary assumption
4. Remember to use rule to discharge all assumption
5. If you find one way is false, please turn to another route

The most important one is **Don't use your brain during deduction yet follow the general rules given in slides**

I will demonstrate the process.

Eg. $\neg (P \land Q) \vdash \neg P \, \lor \, \neg Q$

Easier said than done. More exercise is on worksheet.