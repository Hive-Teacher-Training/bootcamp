---
layout: page
---

# Lists and iteration

## Code examples

```python

# do something a particular number of times
for x in range(10):
  print( x )

# range works
for x in range(10,20):
  print( x )

# or range can step backwards
for x in range( 10, 0, -1):
  print( x )
print "Blast off!"

# do something until a condition is met
sum_to_ten = 0
while x < 10:
  sum_to_ten += x
  x = x + 1

# create a list of things
fruits = ['apple', 'mango', 'kiwi', 'lemon']

# do something with every item in a list
for fruit in fruits:
  print("{} is good for you".format(fruit))

# add to a list
fruits.append('pear')

# remove from a list
fruits.remove('kiwi')

```

## Challenges
<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>


The Karvonen heart rate formula lets an athlete determine what heart rate they
should be achieving for a given intensity of effort as follows:

```
Target Heart Rate = ((max HR − resting HR) × %Intensity) + resting HR
```

Create a program which prompts a user for their resting heart rate and age,
and produces a table of heart rate to effort according to the Karnoven heart rate formula
from 55% to 100% of effort.

```
Enter your age: 38
Enter your resting heart rate: 63

Effort  Heart rate
------  ----------
55      127
60      132
65      138
70      144
75      150
.
.
.
.

```

</div>
<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>


Create a program to prompt the user to guess a number between 1 and 100

- Prompt the user for a number
- if the number entered is correct, end the program
- otherwise, let the user know if they are higher or lower than the actual number

```
james-r@darkstar$ python3 guess-a-number.py

Enter a number: 4
Sorry, my number is higher, try again: 7
Sorry, my number is lower, try again: 6
Sorry, my number is lower, try again: 5
You got it!

```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>



Compare the values in a shopping list with the items available in store. Tell the user which items
are in stock, and which aren't.

```
james-r@darkstar$ python3 shopping eggs flour milk sugar

The store has flour, milk and sugar in stock
The store doesn't have any eggs

```

</div>
