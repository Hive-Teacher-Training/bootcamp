---
layout: page
---

# Input and Output

<p>

Input and output in some form are the basis of much software. Without user input, we cannot do anything useful for them. Without output, we cannot provide them with the answers we have calculated. This exercise and it's challenges cover the basics of printing data to the console and collecting input from our users at the command prompt.

</p>

# Code examples

```python
# Print data out with print
print("Hello, there")
print('Hello, there')
print('Hello', "there")

# Add variables to your strings
name = "Jane Doe"
print("Hello, " + name)
print( "Hello, ", name)

# Use formatting
greeting = "Hello, {}".format(name)
print( greeting )

forename = "Jane"
surname = "Doe"
print( "Hello, {} {}".format(forename, surname))

# pick your variables in any order you like
print( "Hello, {1:} {0:}".format(surname, forename))

# Or use your variables in formatting
print( "Hello, {forename} {surname}")

# Get input from a user with the input function
visiting = input("Who are you visiting today?")
```

## Challenges

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>

Print "Hello, World!"

e.g.

```
Hello, World!
```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>

Prompt the user for their name, print "Hello, " followed by the user's name.

e.g.

```
What's your name? James
Hello, James.
```

</div>


<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>

Prompt the user for their name and hometown and print out a summary of what they have entered.

e.g.

```
What's your name? James
Where do you live, James? Manchester
Hi, James, I hope you enjoy living in Manchester.
```

</div>
