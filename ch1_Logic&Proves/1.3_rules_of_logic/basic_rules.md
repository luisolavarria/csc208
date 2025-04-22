# Notes


 ### Modus Ponens: 

   If A implies B is true and if A is true, then B is true. 
     
### Modus Tollens:  

If A implies B is true, and if B is false, then A is false .  

### Logic Equivalence:  
Two STATEMENT are IDENTICAL, when their TRUE TABLE are IDENTICAL.

# **Rules of Logic (1:3)**

## **Logical Statements and Proofs**

### **Logical Connectives and Their Meaning**
- **Conjunction**: \( P \land Q \) is read "P and Q" and is true when both \( P \) and \( Q \) are true.
- **Disjunction**: \( P \lor Q \) is read "P or Q" and is true when at least one of \( P \) or \( Q \) is true.
- **Implication**: \( P \Rightarrow Q \) is read "If \( P \) then \( Q \)" and is false only when \( P \) is true and \( Q \) is false.
- **Biconditional**: \( P \Leftrightarrow Q \) is read "\( P \) if and only if \( Q \)" and is true when \( P \) and \( Q \) are both true or both false.
- **Negation**: \( \neg P \) is read "Not \( P \)" and is true when \( P \) is false.

### **Truth Conditions for Connectives**
- \( P \land Q \) is true when both \( P \) and \( Q \) are true.
- \( P \lor Q \) is true when at least one of \( P \) or \( Q \) is true.
- \( P \Rightarrow Q \) is false only when \( P \) is true and \( Q \) is false.
- \( P \Leftrightarrow Q \) is true when \( P \) and \( Q \) are both true or both false.
- \( \neg P \) is true when \( P \) is false.

### **Direct Proofs of Implications**
To prove an implication \( P \Rightarrow Q \), assume \( P \) is true and deduce \( Q \) from it.

### **Converse and Contrapositive**
- The **converse** of an implication \( P \Rightarrow Q \) is \( Q \Rightarrow P \). The converse is **not** logically equivalent to the original implication.
- The **contrapositive** of an implication \( P \Rightarrow Q \) is \( \neg Q \Rightarrow \neg P \). The contrapositive **is** logically equivalent to the original implication.

### **Necessary and Sufficient Conditions**
- "\( P \) is necessary for \( Q \)" means \( Q \Rightarrow P \).
- "\( P \) is sufficient for \( Q \)" means \( P \Rightarrow Q \).
- If \( P \) is necessary and sufficient for \( Q \), then \( P \Leftrightarrow Q \).

## **Truth Tables**
### **Truth Table for Implication \( P \Rightarrow Q \)**
| \( P \) | \( Q \) | \( \neg P \lor Q \) |
|---|---|------------|
| T | T | T          |
| T | F | F          |
| F | T | T          |
| F | F | T          |

- The statement is **true** unless \( P \) is **true** and \( Q \) is **false**.

### **Logical Equivalences**
- **Contrapositive Equivalence**:
  - \($ P \to Q$ = ~ $Q \to ~ P $\)
- **De Morgan's Laws**:
  - \($ ~ (P \land Q) = ~ P \lor ~ Q$ \)
  - \( $~ (P \lor Q) = ~ P \land ~ Q$ \)
- **Implications as Disjunctions**:
  - \($ P \to Q $= ~ P \lor Q \)
- **Double Negation**:
  - \( ~ ~ P = P \)

### **Equivalence of Quantified Statements**
- \( ~$ \forall x P(x)$ $\equiv \exists x ~ P(x)$ \)
- \( ~ $\exists x P(x) \equiv \forall x ~ P(x)$ \)