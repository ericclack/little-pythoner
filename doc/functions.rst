.. _functions:

Functions
=========

Learn about functions in Python so that you can package up code into
re-usable blocks, avoid repetition and make your code easier to read. 

Look at each question and see if you can answer it, then check with
the answer we've given. Do try these out in the :ref:`repl`.

**Remember:** *understanding* is the most imporant thing, don't move
on until you really understand the question and answer.

----

What does this expression produce? ::

  2+3

* It produces the result of `2+3` which is `5`

This is a function, what does it do? ::

  def add(a, b):
    return a+b

* It *defines* a function called `add` that we can use later to add
  two numbers together.

How do we call it?

* We write an expression `add(2,5)` which would produce `5`. 

So there's a difference between defining a function and calling a function?

* Yes, we use `def` to define a function then we call it by putting
  brackets after its name, like `add(2,4)`.

Define a function that returns the number 5.

* OK: ::

    def five():
      return 5

This function takes no *arguments* (that's an odd word!) arguments
become variables inside the function.

What arguments does this function take? ::

  def move(angle, direction):
    # to do

* Two arguments: `angle` and `direction`, these become variables
  inside the function.

How are the arguments set?

* The caller provides them when they call the function, like in these
  three examples: ::

    move(45, 10)
    move(-45, 2)
    move(180, 100)

Let's write a little example program, a number guessing game. The
computer generates a random number between 1 and 10 and the user has
to guess it.

What does this code do? ::

  import random
  number = random.randint(1,10)
  print(number)

* It generates a random number between 1 and 10 and prints it out. We
  should keep the number secret until the player guesses correctly!
  
