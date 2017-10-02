---
layout: page
---

# Operators and comparison


<p class="flow-text">

</p>


## Code examples

```python

# numbers can be added
one = 1
three = 1 + 1 + 1
four = 1 + three

# so can strings
salutation = "Hello"
name = "Anya"
greeting = salutation + " " + name

# numbers can't be added to strings, and vice-versa
two = "2"
three = 3
five = three + two           # causes an error
twenty_three = two + three   # also causes an error

# not without converting them into numbers
five = three + int(two)

# and the same the other way around
twenty_three = two + str(three)

# numbers can also be subtracted
minus_one = 6 - 7

# numbers can be multiplied
forty_two = 7 * 6

# divided
four = 24 / 6

# and remainders calculated
six = 14 % 8

# Comparing values

# Numbers can be compared to check if they are equal to, greater than and less than each other
# The result of a comparison is a boolean value, True or False

24 > 12           # True

12.7 > 12.7000001 # False

12.7 == 12.7      # True

5 <= 5            # True

16 >= 15          # True

# strings can also be compared
"This" == "That"   # False

this = "This"

this == this      # True





```


## Challenges


<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>


</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>


</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>


</div>
