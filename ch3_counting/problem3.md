# Exercise number 3: #
  
A group of college students was asked about their TV watching habits. Of those surveyed, 29 students watch The Walking Dead, 24 watch The Blacklist, and 27 watch Game of Thrones. Additionally, 10 watch The Walking Dead and The Blacklist, 13 watch The Walking Dead and Game of Thrones, and 17 watch The Blacklist and Game of Thrones. There are 8 students who watch all three shows. How many students surveyed watched at least one of the shows?
# #
# Counting Students Who Watched At Least One Show

## Problem:
A group of college students was surveyed about their TV-watching habits. The numbers of students watching different shows are:

- **$|W| = 29$** students watch *The Walking Dead*.
- **$|B| = 24$** students watch *The Blacklist*.
- **$|G| = 27$** students watch *Game of Thrones*.
- **$|W \cap B| = 10$** watch both *The Walking Dead* and *The Blacklist*.
- **$|W \cap G| = 13$** watch both *The Walking Dead* and *Game of Thrones*.
- **$|B \cap G| = 17$** watch both *The Blacklist* and *Game of Thrones*.
- **$|W \cap B \cap G| = 8$** watch all three shows.

We aim to find the number of students who watch at least one of the shows.

## Solution Using Inclusion-Exclusion
Applying the **Inclusion-Exclusion Principle**:

$$ |W \cup B \cup G| = |W| + |B| + |G| - |W \cap B| - |W \cap G| - |B \cap G| + |W \cap B \cap G| $$

$$ |W \cup B \cup G| = 29 + 24 + 27 - 10 - 13 - 17 + 8 $$


$$ 80 - 40 + 8 = 48 $$

Thus, the number of students who watched **at least one show** is:

$$ \boxed{48} $$

