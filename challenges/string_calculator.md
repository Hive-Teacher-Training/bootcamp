---
layout: page
---

# Anagrams challenge

<p class="flow-text">

Write a program which takes a string of user input and treats it as a mathematical
calculation, reporting the result of the calculation to the user.

</p>


- Support addition, subtraction, multiplication and division represented by "+", "-", "*", and "/"
- Unrecognised numbers should result in an error being reported to the user,
  indicating the string which was not recognised


e.g.
```
james-r@darkstar$ python3 calculator "4 + 27"
"4 + 27" is 31

james-r@darkstar$ python3 calculator "4 * 7"
"4 * 7" is 28

james-r@darkstar$ python3 calculator "4 + zero"
Error. Unrecognised number "zero"

james-r@darkstar$ python3 calculator "4 over one"
Error. Unrecognised operator "over"

```
