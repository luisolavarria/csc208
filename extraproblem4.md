# Sequence Definition and Recursion

## Part 1: Original Sequence

Given the recursive definition:

$$
a_1 = 3 \\
a_n = 2a_{n-1} + 4 \quad \text{for } n \geq 2
$$

The first few terms of the sequence are:

$$
\begin{align*}
a_1 &= 3 \\
a_2 &= 2(3) + 4 = 10 \\
a_3 &= 2(10) + 4 = 24 \\
a_4 &= 2(24) + 4 = 52 \\
a_5 &= 2(52) + 4 = 108
\end{align*}
$$

So, the sequence is:

$$
3,\ 10,\ 24,\ 52,\ 108,\ \ldots
$$

---

## Part 2: Recursive Definition for the Sequence

Given the sequence:

$$
10,\ 24,\ 52,\ 108,\ \ldots
$$

This is equivalent to the original sequence starting from the second term. We define a new sequence \( b_n \) as:

$$
b_1 = 10 \\
b_n = 2b_{n-1} + 4 \quad \text{for } n \geq 2
$$

This gives us the same recurrence pattern with a new starting value.

---
