---
layout: page
---

# Roman numerals challenge

<p class="flow-text">

Write a program which takes in a numeric string and represents it as Roman numerals.

</p>


- The program should support numbers up to fifty
- Roman numbers are represented as follows
  - 1 = I
  - 5 = V
  - 10 = X
  - 50 = L
- Other numbers are formed additively, with smaller numbers appended to the right hand side of the string
  - e.g. 2 = II, 13 = XII
  - The exception to this rule are cases where a smaller number can be placed to the left of a larger number, and subtracts from the larger:
    - 4 = IV
    - 9 = IX
    - 40 = XL
    - The cases above are the only ones you need consider for your program
- Non-numeric entry should be rejected
- Numbers unsupported by the program should be rejected


e.g.

```
james-r@darkstar$ python3 numerals 21
"21" is "XXI" in roman numerals

james-r@darkstar$ python3 numerals "XXI"
Sorry, "XXI" is not a valid numbers

james-r@darkstar$ python3 numerals 90
Sorry, 90 is too large for this program to compute

```
