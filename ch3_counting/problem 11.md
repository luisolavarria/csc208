## Function Counting Problem

Consider functions  
$$f : \{1, 2, 3, 4, 5, 6\} \to \{1, 2, 3, 4, 5, 6, 7\}$$

### (a) How many functions are there total?

Each of the 6 elements in the domain can be mapped to any of the 7 elements in the codomain.  
So the total number of functions is:

$$7^6 = 117649$$

---

### (b) How many functions are injective?

An injective function assigns **distinct** values to each input.

To count injective functions:
- We choose 6 distinct elements from the codomain of 7 elements: $\binom{7}{6}$
- Then we permute those 6 elements: $6!$

So the number of injective functions is:

$$
P(7, 6) = \frac{7!}{(7-6)!} = 7 \cdot 6 \cdot 5 \cdot 4 \cdot 3 \cdot 2 = 5040
$$

---

### (c) How many of the injective functions are increasing?

An increasing function means:  
If $a < b$, then $f(a) < f(b)$.

To count these:
- Choose any 6-element subset from the codomain (of size 7): $\binom{7}{6}$
- There is only one way to assign them in increasing order.

So the number of increasing injective functions is:

$$
\binom{7}{6} = 7
$$
