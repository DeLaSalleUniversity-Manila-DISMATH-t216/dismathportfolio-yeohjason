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

|                           Equivalence                           |         Name        |
|:-------------------------------------------------------------:  |:-------------------:|
|                      p ∧ T ≡ p <br> p v F ≡ p                   |    Identity laws    |
|                       p v T ≡ T <br> p ∧ F ≡ F                  |   Domination laws   |
|                       p v p ≡ p <br> p ∧ p ≡ p                  |   Idempotent laws   |
|                            ¬(¬p) ≡ p                            | Double negation law |
|                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p              |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                   |    Negation laws    |

- Superman Logic HW: There are a lot variables in this statement which confuses the reader. By applying the rules of inference, we can test the validity of the argument. The argument is valid. Superman does not exist. 
- The idea behind the use of **predicate logic** is comparable to the subject-predicate relationship in English language. We can simplify the proposition or sentence into *subject* and *predicate*.
  - Ex. In the statement "j is equal to 5", the variable 'j' is the subject and the phrase "is equal to 5" is the predicate.
- We were introduced to a new topic: **Quantifiers**. The two types of quantification are the following:
  - *Universal Quantification* - "tells us that a predicate is true for every element under consideration"
  - *Existential Quantification* - "tells us that there is one or more element under consideration for which the predicate is true"


## Week 3:
- I learned that an argument is **valid** if and only if its premises and final proposition are true. If not, then they will lead to invalid argument (**fallacy**).
- Since verifying the validity of an argument through a truth table is a tedious process, **rules of inference** may come handy for students to construct more complex valid argument forms. The rules of inference are as follows:

|   Rule of Inference       |            Tautology           |          Name          |
|:--------------------:     |:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |      Modus ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus tollens     |
|     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical syllogism |
|      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive syllogism |
|       p<br>∴p ∨ q         |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴p         |           (p ∧ q) → p          |      Simplication      |
|      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       |

- We were introduced to methods of constructing proofs.
- **Direct proof** (P → Q): 
  - Steps in constructing Direct Proof:
    1. Assume that P (hypothesis) is true.
    2. Use P to show that Q (conclusion) must be true.


## Week 4:
- **Proof by Contraposition** (¬Q → ¬P): 
  - Steps in constructing Contrapositive/indirect Proof:
    1. Assume that ¬Q is true.
    2. Show that ¬P is also true.
- **Vacuous & Trivial Proofs**: 
  - Vacuous Proof: ¬P → (P → Q)
  - Trivial Proof: Q → (P → Q)
- **Proof by Contradiction**:
  - Steps in constructing Proof by Contradiction:
    1. Assume P is true.
    2. Assume ¬Q is true.
    3. Demonstrate a conclusion.
- Our instructor provided a clear definition of a rational number. 
  - The real number r is rational if there exist integers p and q with q≠0 such that r = p/q. Otherwise, it is an irrational number.
  - Q = {a/b | a, b ∈ ℤ} where b≠0, a & b have no common factor other than ±1


## Week 5:
- tbc.
