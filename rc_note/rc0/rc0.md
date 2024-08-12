# VE203 rc0

Again, welcome to VE203. This is one of my favourate course at Joint Institute. I hope we can share the same feeling at the end of semester. In rc0, I will lead to browse all topics covered in this course and give you some tips on how to grasp the essence of this course.

## Basic Set Theory and Logic

The content in this section connects the `set` we have learned in high school with more interesting properties. A graph is shown below.

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

Many things in this world are not chaotic; rather, there exist some hidden rules. Induction and Recursion employ these rules to find some properties.