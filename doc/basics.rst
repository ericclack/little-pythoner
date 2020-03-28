.. _basics:

The Basics
==========

Learn the basics of the Python programming language. Numbers, strings,
comparisons and variables.

Look at each question and see if you can answer it, then check with
the answer we've given. Do try these out in the :ref:`repl`.

----

What's this? ::

  1

* It's a number. The number one. In Python we often use numbers and
  they are really simple to include in our programs.

Is this a number? ::

  92617384911

* Yes, a big one.

What about this, still a number? ::

  1.28374

* Yes, that's a :code:`float`, which means a floating point number, a
  bit bigger than 1.

If 1.2874 is a :code:`float` what type of number is :code:`123`?

* It is an :code:`int`, which means integer or whole number. 

----
  
What's this? ::

  "Hello"

* It is a :code:`string`, a sequence of characters. 

What's this? ::

  'h'

* It is also a string but with just one character. In Python you can
  use :code:`"` or :code:`'` to mark strings.

So what happens if we do this? ::

  'hello' + 'world'

* It produces the string :code:`'helloworld'`.

How would we get a space in that string?

* We could do one of the following: ::
    
  'hello' + ' ' + 'world'
  'hello ' + 'world'
  'hello' + ' world'

----

Did you remember to try these out in the :ref:`repl`?

----

What does this expression produce? ::

  2 == 1+1

* It tests whether `2` equals the result of `1+1`. It does so it produces `True` .

Is this `True`? ::

  16 == 4*4

* Yes, `16` is the square of `4`.

What about this expression? Is this `True`? ::

  '16' == 16

* No, `False`. A string can never be equal to a number, they are different
  types.

What does this mean, and is it `True`? ::

  5 > 1

* It tests if 5 is greater than 1, and it is so it produces `True`.

What about this expression, `True` or `False`? ::

  5*5 > 4*4 > 3*3

* Well the square of `5` is bigger than the square of `4` and that is
  bigger than the square of `3` so this expression produces `True`.

Here's a tricky one, what does this produce? ::

  5 > 'five'

* This won't work in Python. It raises an exception, a `TypeError`,
  we're told that: :code:`'>' not supported between instances of 'int'
  and 'str'`
* That's good to know!

----

What is this? ::

  v

* It is not yet defined. Python tells us this with a `NameError`.

Does this make more sense? ::

  v = 2
  v*v*v

* Yes, `v` is now a `variable` and we set it to the value `2`. We then
  ask for the cube of `v` and this produces `8`.

What does this do? ::

  greeting = 'hello'
  name = 'eric'
  greeting + ' ' + name

* It creates two variables, one with a greeting and the other with a
  name. It then joins the two together with a space and produces
  'hello eric'.

What about this, what does it do and produce? ::

  greeting = 'Hello'
  name = input('Enter your name: ')
  greeting + ' ' + name

* It creates a greeting variable with a string, then creates a name
  variable using whatever the user types at the prompt. It then produces
  a string containing a greeting.

----

Things are getting a bit more complicated now! Do try these out in the
:ref:`repl`?

----

