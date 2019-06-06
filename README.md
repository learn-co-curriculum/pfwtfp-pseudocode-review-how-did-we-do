# Pseudocode Demonstration: How'd We Do?

## Learning Goals

- Assess a Developer's Pseudocode

## Introduction

According to the Flatiron Process, when you finish writing the pseudocode,
you should move to "Step 6: Verify the procedure's output." Verify that the
pseudocode is correct.

Here's the pseudocode again:

```pre
Procedure DivideBaguetteEvenly(baguette, n):
  baguette_length = measure(baguette)
  even_length = baguette_length / n
  collection = []

  while baguette_length > even_length:
    piece, rest = cut_bread(baguette, even_length)
    collection.add(piece)

    baguette = rest
    baguette_length = measure(baguette)

  even_pieces = collection
  return even_pieces
```

Ask yourself the following questions as you look at this pseudocode. It might
even be worth writing down in a journal or on a piece of paper **your** 
interpretation of this process? Where do you like to start?

* Is it too long? Too short? Too complicated?
* Do assumptions need to be clearer?
* Do you think this pseudocode is correct?
* If you don't think the pseudocode is correct, what do you think is wrong?
* What was your process for verifying the correctness of the pseudocode? Did you write a table of variables and values? Draw a picture? Did you discover anything surprising?
