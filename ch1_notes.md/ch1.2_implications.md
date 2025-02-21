# Chapter 1.2 - Implications

## Vocabulary

- **Implication** (or **conditional**) refers to a logical statement of the form $P \to Q$
    - $P$ and $Q$ are statements 
        - $P$ is the **hypothesis** (or **antecedent**)
        - $Q$ is the **conclusion** (or **consequent**)
    - An implication is considered **true** if $P$ is **false** or $Q$ is true (or both); it is **false** otherwise.
    - An implication is only false if $P$ is true **and** $Q$ is false.

- The statement "$P$ is necessary for $Q$" means $Q \to P$
- The statement "$P$ is sufficient for $Q$" means $P \to Q$
- If $P$ is both necessary and sufficient for $Q$, we write $P \leftrightarrow Q$

## Notes

### Truth Table Representation

- The definition of an implication is often illustrated through a truth table. 
- The implication $P \to Q$ is false only when $P$ is true and $Q$ is false.

### Purpose of Implication

- Implication is a method to describe the relationship between two statements.

### Converse, Contrapositive, and Inverse

- The **converse** of $P \to Q$ is $Q \to P$.
- The **contrapositive** of $P \to Q$ is $\neg Q \to \neg P$.
- The **inverse** of $P \to Q$ is $\neg P \to \neg Q$.
- Both the converse and contrapositive swap the positions of $P$ and $Q$.

### Quantified Statements

- When dealing with quantified statements, the outer quantifiers are ignored when creating the converse, contrapositive, and inverse.
    - A quantified implication like $\forall x (P(x) \to Q(x))$ has:
        - **Converse**: $\forall x (Q(x) \to P(x))$
        - **Contrapositive**: $\forall x (\neg Q(x) \to \neg P(x))$
        - **Inverse**: $\forall x (\neg P(x) \to \neg Q(x))$
    - A statement like $\exists x (P(x) \to Q(x))$ is rarely encountered because it would always be true if there exists an $x$ where $P(x)$ is false.

### Key Properties

- **The contrapositive of a true statement remains true**.
- When both $P \to Q$ and $Q \to P$ hold true, we write $P \leftrightarrow Q$.
- "If and only if" statements can be thought of as consisting of two parts: an implication and its converse.