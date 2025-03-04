# Notes 1.5 & 1.6
### Injective Functions 
When: $A \to B$   
Where:   
$ A = {1, 2, 3, 4}$   
$ B = {a, b, c, d} $  
 
 B is the image of at most one element in A.
 In other words, no element in B 
 is the **output** for more than one **input** from A.  
  Then:  
  $ f(1) = a, f(2) = b, f(3) = c, f(4) = d. $
  ### Element Chasing  
  We will give a direct proof. Let A, B
 , and C be sets, and assume that $ A \subseteq B $ and $B \subseteq C$.
 We will prove that $A \subseteq C$.

## Introduction
Logic provides the framework for constructing mathematical proofs. While logic gives structure, mathematical content gives meaning. This chapter explores the importance of both elements in proof construction.

## Logical Structures and Mathematical Content
A proof consists of:

- **A logical skeleton**: The structure of the argument.
- **Mathematical flesh**: The actual content and reasoning.

Understanding both components ensures a rigorous and clear proof.

## Examples and Explanation

### Mini Sudoku Proofs  
To illustrate the importance of logical structure and mathematical reasoning, the text presents the following example.

| A | B | A → B |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | T     |
| F | F | T     |

### Understanding Proofs in Different Contexts  
Sometimes, familiar facts seem obvious, making their proofs non-trivial. Analyzing problems in different contexts (e.g., Sudoku puzzles) strengthens proof-writing skills.

## Conclusion
Both logic and mathematical reasoning are essential in proof writing. Developing skills in constructing rigorous arguments ensures clarity and correctness in mathematical reasoning.

## Proofs of Discrete Structures

### Definitions
- **Set**: An unordered collection of elements.
- **Element chasing**: Basically syllogism.
- **Injective**: No element of one set is the output of more than one input of another set (one-to-one).
- **Domain**: Inputs of a function.
- **Codomain**: Outputs of a function.
- **Relation**: A set of ordered pairs.
- **Corollary**: When a theorem or proposition is applied to prove another result directly.

### Subsets  
A set $A$ is a **subset** of a set $B$, written $A \subseteq B$, provided every element of $A$ is also an element of $B$. This makes $B$ a **superset** of $A$.  

$A$ is a **proper subset** of $B$, written $A \subset B$, provided $A \subseteq B$ and $A \neq B$. In other words, if every element in $A$ is an element in $B$, and there is at least one element in $B$ that is not in $A$.  

For any sets $A$, $B$, and $C$, if $A \subseteq B$ and $B \subseteq C$, then $A \subseteq C$.  

### Functions  
A function $f: A \to B$ is a rule that assigns every element of set $A$ exactly one element of set $B$.  

Given a function $f: X \to Y$ and a set $A \subseteq X$, the **image of A under f** is the set:  
$$ f(A) = \{f(a) \in Y \mid a \in A\} $$  
That is, $f(A)$ is the set of all outputs of the function for inputs in $A$.  

### Relations  
A relation $R$ on a set $A$ is **transitive** if, for all $x, y, z \in A$,  
if $xRy$ and $yRz$, then $xRz$.  
