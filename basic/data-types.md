---
layout: post
---

# Variables and data types


<p class="flow-text">

</p>


## Code examples

```python

# variables are assigned by declaring a name, and setting them equal to a value
foo = "bar"

# variables can be re-assigned once they're declared
foo = "baz"

# Numbers
ten = 10
one_hundred = 100
float = 2.2
pi = 22/7

just_an_integer = ten + one_hundred

very_floaty = float * float
still_a_float = float * integer

# Strings
forename = "Jane"
surname = "Doe"
fullname = forename + ' ' + surname

# Booleans
truthy = True
falsey = False

# There's even the idea that something exists, but it's nothing
the_void = None

```

## Challenges

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>

Use your console window to start python and check what happens when you assign a variable and then type the variable name.

e.g.

```shell
james-r@sycorax$ python3
Python 3.6.1 (default, Apr  4 2017, 09:40:21)
[GCC 4.2.1 Compatible Apple LLVM 8.1.0 (clang-802.0.38)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> foo = "bar"
>>> foo
'bar'
>>>
```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>

Starting python in your console again, assign variables for numbers, strings, and boolean values, like the examples above.

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>

Use your console to see the difference between a declared variable with no value (```None```) and a variable you haven't declared.

</div>
