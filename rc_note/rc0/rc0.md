# VE203 rc0

Again, welcome to VE203. This is one of my favourate courses at Joint Institute. I hope we can share the same feeling at the end of semester. 

In rc0, I will lead to browse all topics covered in this course and give you some tips on how to grasp the essence of this course. VE203 is interesting, however, as its name indicates, is discrete. I hope these graphs can help you have a glance at the course in the beginning of the semester.

## Basic Set Theory and Logic

The content in this section connects the `set` we have learned in high school with more interesting properties. This is fundamental in many field, including computer science. There are many concepts and they are related. A graph is shown below.

```mermaid
    graph
    A(["Set"])
    B(["Multiset"])
    C(["Set Notation"])
    D(["Set Operation"])
    E(["Set Algebra"])
    F(["Cartesian Product"])
    G(["Simple Graph"])
    H(["Directed Graph"])
    A <--> B
    A --> C
    A --> D
    C --> E
    D --> E
    D --> F
    AA(["Proposition"])
    AB(["Connectives"])
    AC(["Boolean Algebra"])
    AA <--> A
    AA --> AB
    AB <--> D
    AA --> AC
    AB --> AC
    E <--> AC
    AD(["Truth Tree"])
    AE(["Natural Deduction"])
    AC --> AD
    AC --> AE
    G <--> H
    AF(["Predicate"])
    AG(["Quantifier"])
    AF --> AA
    AG --> AA
```

## Induction and Recursion

Many things in this world are not chaotic; rather, there exist some hidden rules. Induction and Recursion employ these rules to find some properties. Induction is useful to learn new things. For instance, we use induction to verify the correctness of an algorithm. A graph below shows what we will learn.

```mermaid
    graph
    A(["Induction"])
    B(["Complete Induction"])
    C(["Recursive Definition"])
    D(["Structural Induction"])
    E(["Mathcmatical String"])
    F(["Proof"])
    G(["Monoid"])
    H(["WOP"])
    A ---> B
    A ---> D
    C --> D
    C --> E
    E --> D
    A --> F
    B --> F
    D --> F
    G --> E
    H --> F
```

## Relation, Function and Order

These are important topics in this course. We are discussing interesting relations between numbers, functions and exploring order of things. Relation is important for algorithm.

```mermaid
    graph
    A(["Relation"])
    B(["Function"])
    C(["Domain and Codomain"])
    D(["Partial Function"])
    E(["Operation"])
    F(["Injection and Surjection"])
    G(["Properties of Relation"])
    H(["Equivalence Class"])
    I(["Partition"])
    J(["Quotient Set"])
    K(["Monoid Homomorphism"])
    L(["Special Topic: Partial Order"])
    A --> B
    B --> C
    A ----> D
    A --> E
    B --> F
    A -----> G
    G --> H
    G --> I
    I --> J
    H --> J
    J --> K
    A --> L
```

## Numbers and Equinumerosity

We will explore how people find new numbers. Equinumerosity in some way shows relationship between two sets or fields. With this, we can explore more about a set.

```mermaid
    graph
    A(["Number Expansion"])
    B(["Equinumerosity"])
    C(["Cantor's Theorem"])
    D(["Dominance"])
    E(["Cantor-Schröder-Bernstein Theorem"])
    A --> B
    B --> C
    B --> D
    B --> E
    D --> E
```
## Pigeonhole Principle

This is not a new friend. Most of us are already familiar with him. With the principle, we can easily do some proof. We won't dive deep into it, and graph below shows the content.

```mermaid
    graph 
    A(["Finite Set"])
    B(["Pigeonhole Principle(both versions)"])
    C(["Cardinality of a Set"])
    D(["Applications"])
    E(["Erdős–Szekeres Theorem"])
    A --> B
    A --> C
    B --> C
    B --> D
    D --> E
```

## Partial Order


Partial order is a special topic here. It will be discussed after mid-term exam. It reveals a special but fundamental relation between things. A graph below shows what we will learn.

```mermaid
    graph
    AAA(["Partial Order"])
    AA(["Coset"])
    AB(["Hasse Diagram"])
    AC(["Elements"])
    AD(["Comparability"])
    AE(["Chain"])
    AF(["Antichain"])
    AG(["Mirsky’s Theorem"])
    AH(["Dilworth’s Theorem"])
    AAA --> AA --> AB --> AC
    AB --> AD
    AC --> AD
    AC --> AE
    AC --> AF
    AE --> AG
    AF --> AH
```