
#### We roll five dice, each with six faces. Since the order of the dice does not matter, we treat identical rolls as the same outcome. This means instead of considering all possible ordered sequences, we count only the distinct groups of dice results.
  ### We apply the Stars and Bars Formula:



$$
\binom{n+r-1}{r} = \frac{(n + r - 1)!}{r!(n-1)!}
$$    
For Yahtzee (5 dice, 6 faces):
where we roll five regular 6-sided dice:
- \( n = 6 \) (number of distinct die faces),
- \( r = 5 \) (number of dice rolled).


$$\binom{6 + 5 - 1}{5} = \binom{10}{5} = \frac{10!}{5!(10-5)!} = \frac{10!}{5!5!} = 252$$

#### Now we roll six dice, each with five faces. Since the order of the dice does not matter, we need to count the number of possible unordered outcomes.
For Super-Yahtzee (5 dice, 6 faces):
where we roll six regular 5-sided dice:
- \( n = 5 \) (number of distinct die faces),
- \( r = 6 \) (number of dice rolled).



Applying the formula:

$$
\binom{10}{6} = \frac{10!}{6!(10-6)!}
$$

Expanding factorials:

$$
\frac{10!}{6!4!} = \frac{10 \times 9 \times 8 \times 7}{4 \times 3 \times 2 \times 1}
$$

$$
= \frac{5040}{24} = 210
$$





