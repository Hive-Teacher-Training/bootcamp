---
layout: page
---

# Functions

## Code examples

```python

# define functions to split your program into more comprehensible chunks
def display_help():
  print("SkyNet help")
  print("Copyright Cyberdyne systems 1997")
  print("\tType target name and year to dispatch terminator unit")

# functions become more useful if we pass arguments to them
def say_hello(name):
  print("Hello, {}".format(name))

# functions can take many arguments
def print_user_details( name, age, location):
  print("User {} is {} and based at {}".format(name, age, location))

# functions can use default values in case one isn't provided
def say_hello(name = "Anonymous Coward"):
  print("Hello, {}".format(name))

# functions can return values
def add_numbers(first, second):
  return first + second

def compose_greeting(name="Anonymous Coward"):
  greeting = "Hello, {}".format(name)
  return greeting

```


## Challenges

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>

Create a program that calls a function, `containsNumber`, which prompts the user for an input
string and then informs them whether or not the string contains a number.

e.g.

```
Enter a string of characters: qazw2
qazw2 contains a number.

Enter a string of characters: plokm
plokm does not contain a number.
```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>

Create a program that asks the user for two numbers, and tells them whether either number is a factor of the other.
Your program should contain a function, `factorOf`, which takes two integer parameters and returns
true or false if the first number supplied is a factor of the second number.

e.g.

```
Enter a number: 10
Enter another number: 18
18 is not a factor of 10.

Enter a number: 6
Enter another number: 3
3 is a factor of 6.

Enter a number: 2
Enter another number: 10
2 is a factor of 10.

```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>

Create a program which checks the strength of a user entered string as a password.

Passwords come in 3 strengths; weak, strong and very strong

* weak passwords contain only numbers or only characters and are less than ten characters in length.

* strong passwords contain numbers and characters and are at least ten characters long.

* very strong passwords contain numbers, characters and non-alphanumeric characters
and are more than ten characters long.

Make sure that you write functions for each of the checks you will have to make to the password string,
and combine them to report the user's password strength.

e.g.

```
Enter a password: liverpool
liverpool is a weak password

Enter a password: 90210
90210 is a weak password

Enter a password: m4nchester
m4nchester is a strong password

Enter a password: w4rr!ngton
w4rr!ngton is a very strong password
```

</div>
