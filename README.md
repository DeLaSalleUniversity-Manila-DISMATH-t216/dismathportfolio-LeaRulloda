# My DISMATH Portfolio
dismathportfolio-LeaRulloda created by Classroom for GitHub
##Week 1
- I was introduced to the course DISMATH, which is quite different from my other mathematics subjects for it deals with logic, algorithms, proofs, and other things I’m yet to learn.
- On our first week of classes, I learned that there are different kinds of truth such as legal, authoritative, scientific, probable, and philosophical truth. What we’re trying to learn in this course is the **mathematical proof** which is a chain of logical deductions leading to the proposition from a base set of axioms.
- I learned symbols such as:

| Logical Symbol  |  Logical Operator | Shorthand | Logical Expression | Value |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | ¬p | opposite |
| ∧ | Conjunction | and | p ∧ q | minimum |
| v | Disjunction | or | p v q | maximum |
| ⊕ | Exclusive disjunction | xor |  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) | T iff exactly one of p and q is T, otherwise F|
| → | Conditional | if, then | p → q ≡  ¬p v q | F if p is T and q is F, otherwise T |
| ↔ | Biconditional | iff |  p ↔ q ≡ (p → q) ∧ (q → p) |  T iff p and q have the same truth values |

- I learned proving by using a truth table. The number of rows in a truth table is determined by the equation **rows = 2^n** where n is the number of variables.
- I learned the **Implication Equivalence** which states that p → q ≡ ¬p v q.
- In a conditional statement for example p → q, I learned that p is called the **antecedent** and q the **consequent**.
- I encountered new common conditional statements such as the converse, contrapositive, and inverse. I learned that a conditional statement and its contrapositive are equivalent as proved using a truth table below.

| p	q | p → q | Inverse <br> ¬p → ¬q | Contrapositive <br> ¬q → ¬p | Converse q → p |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| F	F | T | T | T | T |
|F	T | T | F | T | F |
|T	F | F | T | F | T |
|T	T | T | T | T | T |

##Week 2
- I learned some logical equivalences:
![logical equivalences] (https://dlsuedu-my.sharepoint.com/personal/lea_rulloda_dlsu_edu_ph/_layouts/15/guestaccess.aspx?guestaccesstoken=4W5jSlS7G08%2fr%2bw24FuBYSy1FdiIxBzPBYZCqKpkBM4%3d&docid=049d2ece215ac4308baad271f2b865baa)
- I learned about predicates and quantifiers. I learned that a **predicate** refers to the property that a subject of a statement can have while **quantifiers** indicates the generality of the open sentence in which a variable occurs.
- I learned the two types of quantifiers, the **universal quantifier**, which indicates that a predicate is true for every element considered, and **existential quantifier**, which implies that there is one or more element in the domain for which the predicate is true.
![Quantifiers] (https://dlsuedu-my.sharepoint.com/personal/lea_rulloda_dlsu_edu_ph/_layouts/15/guestaccess.aspx?guestaccesstoken=%2bz%2f4kgKmGKVgedTl1%2bigb31h3W4iu%2bjMXQ9HcgBCeLo%3d&docid=040ea944deb5648ed8c19f7b9a06fc32c)
- I learned that universally-quantified statements can be disproven if there’s even one counterexample while existentially-quantified statements are already true if there’s at least one positive example.
- We were also given some common examples of **fallacies**: <br>
p → q <br>
q <br>
∴ q :-1: 

	p <br>
∴ p ∧ q :-1: 

##Week 3
- I learned about the **rules of inference**:
![rules of inference] (https://dlsuedu-my.sharepoint.com/personal/lea_rulloda_dlsu_edu_ph/_layouts/15/guestaccess.aspx?guestaccesstoken=QSfo6SdX9YHkta%2b1b9WdIhbJ1mIdVRb0vPIx%2fVRSbZ0%3d&docid=08c9b3b78aa724b05993aec87fff9f130)
- I was able to understand the logical equivalences and the rules of inference by answering our assignment about superman, I was able to prove that he doesn’t exist.
- This week, we were introduced to proofs and the different **methods of proving**, I learned how to prove using these methods:
  - **Direct Proof** 
     - a. Assume that p is true
     - b. Show that q is true
  - **Indirect Proofs**
    - **Proof by Contraposition**
      - a. Assume that ¬q is true
      - b. Show that ¬p is true
    - **Vacuous Proof**
      - a. show that p is false
    - **Trivial Proof**
      - a. show that q is true

##Week 4
- Our lesson for this week was a continuation of the different methods of proving namely:
    - **Proof by Contradiction**
      - a. Assume that the negation of the whole premise is true, that is ¬P is true
      - b. Show that it leads to a contradiction
    - **Proof by Equivalence**
      - a. Show that p → q is true
      - b. Show that q → p is also true
- We then proceeded to **mathematical induction**, which is a proof technique used to prove results about a wide range of objects. It has two parts:
    - a. Basis Step:
      - Verify that P(1) is true
    - b. Inductive Step:
      - Show that P(k) → P(k+1) is true for all positive integers k
- I learned about **recursively defined functions** which are defined by specifying how terms of the sequence are found from previous terms.
- I also learned that there are two steps in using recursive or inductive definition:
   - a. Basis Step:
     - Specify the value of the function at zero.
   - b. Recursive Step:
     - Give a rule for finding its value at an integer from its values at smaller integers.

##Week 5
- We were introduced to **recursive algorithms** which are algorithms that successively reduce a problem to the same problem with smaller input. We were also given some examples.
- I learned about **program correctness**. A program is said to be correct if it produces the correct output for every possible input. A program is not proven to be correct just by testing it with a sample input, instead it is proven through **program verification**.
  - **Program Verification** consists of two parts:
   - a. Partial Correctness
    - shows that the correct answer is obtained if the program terminates.
    - **Hoare triple**
     - notation that indicates that the program, S is partially correct with respect to the initial assertion p and the final assertion q.
   - b. The second part shows that the program always terminates.
- Representation of functions as **power series** was discussed. It can be thought of as a function of x that is defined inside the interval of convergence. The **Zeno’s paradox** was also mentioned. 
- **Sets**
  - A set is an unordered collection of distinct objects, which may be anything (including other sets).
  - **Empty Set**
    - contains no elements
    - denoted by { } or ∅
    - not equal to {∅}
  - **Set-builder Notation**
    - used to describe complex sets mathematically
    - {x | some property that x satisfies}
  - **Subsets**
    - A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T.
  - **Cardinality**
    - the number of elements a set contains
    - For a certain set S, its cardinality is denoted by |S|.

##Week 6
 - We had a review for the upcoming first quiz and we 
 - A session was devoted to a review for the upcoming first quiz. It was concentrated on nested quantifiers.
 - **Functions**
  - also called mappings or transformations
  - Let A and B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.
  - **Types**
      - **One-to-one or Injunction**
        - functions that never assign the same value to two or more different domain elements
      - **Onto or Surjection**
        - every member of the codomain is the image of some element of the domain
      - **One-to-one Correspondence or Bijection**
        - functions that are both one-to-one and onto

##Week 7
:tada: NO CLASSES :tada:

##Week 8
