# dismathportfolio-yeohjason
dismathportfolio-yeohjason created by Classroom for GitHub

## Week 1:
- In this week, I was introduced to an odd but interesting subject called **Discrete Mathematics** (DISMATH).
- I learned that a *proposition* is a declarative statement which can be either true (1) or false (0), but cannot be both.
- I've learned the usage, as well as its formulas/logical expressions, of the following logical symbols:

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
- **Terminologies** (from Chapter 1.3)
  - A **tautology** is a compound proposition that is always true, no matter what the truth values of the propositional variables that occur in it. 
  - A **contradiction** is a compound proposition that is always false. 
  - A **contingency** is a compound proposition that is neither a tautology nor a contradiction.
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
  - *Universal Quantification* (∀) - "tells us that a predicate is true for every element under consideration"
    - To disprove this statement, one can use a counterexample.
  - *Existential Quantification* (∃) - "tells us that there is one or more element under consideration for which the predicate is true"


## Week 3:
- I learned that an argument is **valid** if and only if its premises and final proposition are true. If not, then they will lead to invalid argument (**fallacy**).
- **circular reasoning** or **begging the question**: reasoning where one or more steps are based on the truth of the statement being proved
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
- **Terminologies** [from Chapter 1.7]
  - A **theorem** is a statement that can be shown to be true. Also, it can referred to as *facts* or *results*.
  - A **proof** is a valid argument that establishes the truth of a theorem. 
  - The statements used in a proof can include **axioms** (or *postulates*).
  - A **lemma** (plural *lemmas* or *lemmata*) is considered as a less important theorem that is helpful in the proof of other results.
  - A **corollary** is a theorem that can be established directly from a theorem that has been proved. 
  - A **conjecture** is a statement that is being proposed to be a true statement, usually on the basis of some partial evidence, a heuristic argument, or the intuition of an expert.
  - **Indirect proofs** do not start with the premises and end with the conclusion.
- **Methods of Proof**
  1. Direct Proof
  2. Proof by Contraposition (Indirect)
  3. Vacuous and Trivial Proofs
  4. Proof by Contradiction (Indirect)
  5. Proof by Equivalence
  6. Mathematical Induction
- [1/6] **Direct proof** (P → Q): 
  - Steps in constructing Direct Proof:
    1. Assume that P (hypothesis) is true.
    2. Use P to show that Q (conclusion) must be true.


## Week 4:
- [2/6] **Proof by Contraposition** (¬Q → ¬P): 
  - Steps in constructing Contrapositive Proof:
    1. Assume that ¬Q is true.
    2. Show that ¬P is also true.
- [3/6] **Vacuous & Trivial Proofs**: 
  - Vacuous Proof: It is a proof that P → Q is true based on the fact that P is false.
    - ¬P → (P → Q)
  - Trivial Proof: It is a proof that P → Q is true based on the fact that Q is true.
    - Q → (P → Q)
- [4/6] **Proof by Contradiction**:
  - Steps in constructing Proof by Contradiction:
    1. Assume P is true.
    2. Assume ¬Q is true.
    3. Demonstrate a contradiction.
- Our instructor provided a clear definition of a rational number. 
  - The real number *r* is *rational* if there exist integers p and q with q≠0 such that **r = p/q**. Otherwise, it is an *irrational number*.
  - Q = {a/b | a, b ∈ ℤ} where b≠0, a & b have no common factor other than ±1


## Week 5:
- [5/6] **Proof by Equivalence** (Biconditionals):
  - P ↔ Q ≡ (P → Q) ∧ (Q → P)
  - Steps in constructing Proof by Equivalence:
    - Show P → Q is true.
    - Show Q → P is true.
  - *Proof by cases*: a proof broken into separate cases, where these cases cover all possibilities
- [6/6] **Mathematical Induction**:
  - The **principle of mathematical induction** states that: "If it starts true and its stay true then it's always true."
  - **Mathematical induction** can be inferred to as a **domino effect**. 
    - (1) The first domino falls. 
    - (2) When any domino falls, the next domino falls.
    - Therefore, all dominos will fall!
  - Steps in constructing Mathematical Induction:
    1. Show (not ~~assume~~) P(1) or P(0) to be true.
    2. Assume P(k) is true.
    3. Show P(k+1) to be true.

