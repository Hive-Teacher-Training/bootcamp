---
layout: post
---

# Conditional logic


<p class="flow-text">
To make a program with interesting results, we're almost always going to have to make some decisions, whether on direct input, derived data or information from another source, such as a database or web service.
</p>


## Code examples

```python

if name == "neo":
  activate_matrix()

if bid < maximum_bid :
  place_bid(bid)
  print("Bid of {} placed.".format(bid))
else :
  print( "Cannot place bids over {}.".format(maximum_bid) )

if music_genre == "jazz":
  print "Nice."
elif music_genre == "metal":
  print "Rock on."
else :
  print "Nice tune."

if film_genre == "family" and film_rating > 8:
  print "A laugh out loud family comedy"
elif film_rating > 8:
  print "Highly recommended"
else:
  print "Some like it. Some don't"

```

## Challenges


<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge One</p>


```

Enter a language: French
Enter a name: Peter

Bonjour, Peter

Enter a language: Galacian
Enter a name: Gwendolyn

Sorry, Gwendolyn, I don't speak Galacian

```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Two</p>

Write a program to advise users what they should take with them when they leave the
house, depending on the temperature and probability of rain.

* If it is likely to rain (probability greater than 50%), rain protection should be taken.

* If the temperature is cool, (less than 16 degrees), a coat should be taken; waterproof or not
depends on the chance of rain.

* In warm weather, users can take an umbrella and leave their coats at home.


```

Enter outdoor temperature: 12
Enter probabliity of rain: 60

Take a waterproof

Enter outdoor temperature: 16
Enter probabliity of rain: 80

Take an umbrella

Enter outdoor temperature: 19
Enter probabliity of rain: 25

Chance it with a t-shirt

```

</div>

<div class="card-panel flow-text" markdown="1">
<p class="card-title">Challenge Three</p>


```



```

</div>
