# Notes on Logic Proofs

## Introduction
Logic provides the framework for constructing mathematical proofs. While logic gives structure, mathematical content gives meaning. This chapter explores the importance of both elements in proof construction.

## Logical Structures and Mathematical Content
A proof consists of:
- A logical skeleton: The structure of the argument.
- Mathematical flesh: The actual content and reasoning.

Understanding both components ensures a rigorous and clear proof.

## Examples and Explanation

### Mini Sudoku Proofs
To illustrate the importance of logical structure and mathematical reasoning, the text presents the following example.

| $ A $ | $ B $ |$ A \to  B $|
| ----- | ----- | ---------- |
| $ T $ | $ T $ |    $ T $   |
| $ T $ | $ F $ |    $ F $   |
| $ F $ | $ T $ |    $ T $   |
| $ F $ | $ F $ |    $ T $   |


### Understanding Proofs in Different Contexts
Sometimes, familiar facts seem obvious, making their proofs non-trivial. Analyzing problems in different contexts (e.g., Sudoku puzzles) strengthens proof-writing skills.

## Conclusion
Both logic and mathematical reasoning are essential in proof writing. Developing skills in constructing rigorous arguments ensures clarity and correctness in mathematical reasoning.

### Direct:
Start: We assume $P$ is true  
End: Therefore $Q$ is true

### Contrapositive:
Start: We assume $Q$ is negative  (~Q)  
End: Therefore $P$ is negative (~P)

### Contradiction:
Start: We assume $ (P \to Q)$ is negative (~(P $\to$ Q))  
End: ...which is a contradiction.