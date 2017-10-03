---
layout: page
---

# Scope

## Code examples

```python

salutation = "Hello"

print( "{}, world!".format(salutation))

# this function uses the global `salutation` variable defined above
def greet():
  print( "{}, world!".format(salutation))

# this function will use it's locally defined value for `salutation`, instead of
# the global one
def greet_local_scope():
  salutation = "Aloha"
  print("{}, world!".format(salutation))

# if we need to change global scope within a function, we need to let
# python know by declaring a variable `global`
def change_salutation(new_salutation):
  global salutation
  print("{}, world!".format(salutation))
  salutation = new_salutation
  print("{}, world!".format(salutation))



def multilingual_salutation(language):
  salutation = "Hello"
  if language == "French":
    salutation = "Bonjour"
  elif language == "Hawaian":
    salutation = "Aloha"

  print("{}, world!".format(salutation))

greet()
greet_local_scope()
change_saluation("Hi")
multilingual_salutation("French")
multilingual_salutation("German")

```

## Challenges
