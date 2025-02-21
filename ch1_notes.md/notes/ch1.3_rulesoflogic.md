# Chapter 1.3 - Rules of Logic

## Key Concepts

### Tautology
- A tautology is a statement that is **always true** due to its logical form.
  
### Logical Equivalence
- Two statements are logically equivalent if they are either both true or both false. This means that they must have identical truth values in every possible situation.
- Logical equivalence between two statements is denoted as **$P \equiv Q$**, meaning:
  - $P$ is true if and only if $Q$ is true.
  - Example: $\neg P \lor Q$ and $P \to Q$

### Deduction Rule
- A deduction rule is a **valid argument form** that guarantees the conclusion is true if the premises are true.

---

## Detailed Explanations

- **Logic and Context**: Logic is independent of the context or the meaning of atomic statements or predicates. It focuses solely on the structure of logical forms.
  
- **Truth Tables**:
  - Truth tables are useful tools to track all possible outcomes for logical statements.
  - To test if two statements are logically equivalent, **create a truth table** and compare the truth values for each statement across all rows. If the values match in every case, the statements are logically equivalent.
  
- **Implications as Disjunctions**: Every implication can be expressed as a disjunction:
  - Example: $P \to Q \equiv \neg P \lor Q$
  
- **Double Negation**: Negating a statement twice results in the original statement:
  - Example: $\neg \neg P \equiv P$

- **Quantifiers in Logical Equivalence**:
  - Two statements involving quantifiers can be logically equivalent, but sometimes the equivalence depends on the quantifiers, not the predicates.
  - **Negating Quantifiers**:
    - Negating a universal quantifier ($\forall$) results in an existential quantifier ($\exists$), and vice versa.
      - $\neg \forall x P(x) \equiv \exists x \neg P(x)$
      - $\neg \exists x P(x) \equiv \forall x \neg P(x)$
  - **Universal Quantifiers**: Universal quantifiers resemble conjunctions (AND).
  - **Existential Quantifiers**: Existential quantifiers resemble disjunctions (OR).

- **Predicate Logic**: Predicate logic extends propositional logic, enabling the inclusion of predicates and quantifiers.

---

## Theorems & Laws

### Theorem: Contrapositive Equivalence
- An implication is logically equivalent to its **contrapositive**. 
  - **Example**: $P \to Q \equiv \neg Q \to \neg P$
  - **Proof**: This can be verified using truth tables to show both sides are logically equivalent.

### De Morgan's Laws
- De Morgan's Laws describe the relationship between negations and logical connectives:
  - **Negation of a Conjunction**: $\neg (P \land Q) \equiv \neg P \lor \neg Q$
  - **Negation of a Disjunction**: $\neg (P \lor Q) \equiv \neg P \land \neg Q$

### Negation of an Implication
- The negation of an implication is a **conjunction**:
  - **Example**: $\neg (P \to Q) \equiv P \land \neg Q$
  - An implication is false only if the hypothesis is true and the conclusion is false.