# dismathportfolio-yeohjason
dismathportfolio-yeohjason created by Classroom for GitHub

## Week 1:
- In this week, I was introduced to an odd but interesting subject called **Discrete Mathematics** (DISMATH).
- I learned that a *proposition* is a declarative statement which can be either true (1) or false (0), but cannot be both.
- I've learned the usage, as well as its logical equation, of the following operators/symbols:

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |
- I knew how to verify a statement by using a Truth Table.
- Also, I've learned the different propositional logic such as:
  - Inverse of p → q: ¬p → ¬q
  - Converse of p → q: q → p
  - Contrapositive of p → q: ¬q → ¬p (which also happens to be the equivalent value of the original statement)

## Week 2:
- If Algebra has a variety of laws and rules in solving mathematical equations, Discrete Mathematics has its own set of laws and rules too. These are called **logical equivalences**. These are as follows:

|                           Equivalence                          |         Name        |
|:--------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p  //     p v F ≡ p               |    Identity laws    |
|                       p v T ≡ T  //    p ∧ F ≡ F               |   Domination laws   |
|                       p v p ≡ p //     p ∧ p ≡ p               |   Idempotent laws   |
|                            ¬(¬p) ≡ p                           | Double negation law |
|                   p v q ≡ q v p // p ∧ q ≡ q ∧ p               |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) // (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) //  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q // ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p // p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T // p ∧ ¬p ≡ F                   |    Negation laws    |

- Superman Logic HW: There are a lot variables in this statement which confuses the reader. By applying the rules of inference, we can test the validity of the argument. The argument is valid. Superman does not exist. 
- The idea behind the use of **predicate logic** is comparable to the subject-predicate relationship in English language. We can simplify the proposition or sentence into *subject* and *predicate*.
  - Ex. In the statement "j is equal to 5", the variable 'j' is the subject and the phrase "is equal to 5" is the predicate.
- We were introduced to a new topic: **Quantifiers**. The two types of quantification are the following:
  - *Universal Quantification* - "tells us that a predicate is true for every element under consideration"
  - *Existential Quantification* - "tells us that there is one or more element under consideration for which the predicate is true"

## Week 3:
- I learned that an argument is **valid** if and only if its premises and final proposition are true. If not, then they will lead to invalid argument (**fallacy**).
- Since verifying the validity of an argument through a truth table is a tedious process, **rules of inference** may come handy for students to construct more complex valid argument forms. The rules of inference are as follows:

|   Rule of Inference  |            Tautology           |          Name          |
|:--------------------:|:------------------------------:|:----------------------:|
|       p, p→q ∴q      |        (p ∧ (p → q)) → q       |      Modus ponens      |
|     ¬q, p→q ∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus tollens     |
|     p→q, q→r ∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical syllogism |
|      p∨q, ¬p ∴q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive syllogism |
|       p ∴p ∨ q       |           p → (p ∨ q)          |        Addition        |
|       p ∧ q ∴p       |           (p ∧ q) → p          |      Simplication      |
|      p, q ∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q, ¬p ∨ r ∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       |

- We were introduced to methods of constructing proofs.
- **Direct proof** (P → Q): 
  - Steps in constructing Direct Proof:
    1. Assume that P (hypothesis) is true.
    2. Use P to show that Q (conclusion) must be true.
