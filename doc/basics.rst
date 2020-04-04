.. _basics:

The Basics
==========

Learn the basics of the Python programming language. Numbers, strings,
comparisons and variables.

Look at each question and see if you can answer it, then check with
the answer we've given. Do try these out in the :ref:`repl`.

**Remember:** *understanding* is the most imporant thing, don't move
on until you really understand the question and answer.

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
  
* Yes, that's a `float`, which means a floating point number, a
  bit bigger than 1.

If 1.2874 is a `float` what type of number is `123`?

* It is an `int`, which means integer or whole number.

What type of number does this expression produce? ::

  9/3

* It produces an `int` because `9/3` equals `3` exactly.

What type of number is produced here? ::

  1/3

* It produces a `float` because `1/3` is (very nearly) equal to
  `0.3333333333333333`.

----
  
What's this? ::

  "Hello"

* It is a `string`, a sequence of characters. 

Is this a string? ::

  'h'

* It is also a string but with just one character. In Python you can
  use `"` or `'` to mark strings.

Is this a string? ::

  'abcdef

* No, we start it with a `'` but don't finish it. Python lets us know with
  an exception: `SyntaxError: EOL while scanning string literal`

What about this, is it a string? ::

  'one two three four five"
  
* No, somehow we changed our mind whether to use `'` or `"`. We have to
  use the same one at the start and end of the string. 
  
What happens if we do this? ::

  'hello' + 'world'

* `+` can join two strings together. It produces the string `'helloworld'`.

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
  we're told that: `'>' not supported between instances of 'int'
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

What about this, what does it do, and what does it produce? ::

  greeting = 'Hello'
  name = input('Enter your name: ')
  greeting + ' ' + name

* It creates a greeting variable with a string, then creates a name
  variable using whatever the user types at the prompt. It then produces
  a string containing a greeting for the user. 

----

Things are getting a bit more complicated now! Do try these out in the
:ref:`repl`?

----

What does this do? ::

  v = 5
  v*v
  v = v - 1
  v*v

* It creates a variable called `v` and sets it to `5` and then
  produces the square of `5` which is `25`, it then reduces `v` by one
  so that it becomes `4` and produces the square of this which is
  `16`.

How could we produce all the square numbers between `25` and `1`? ::

  v = 5
  v*v
  v = v - 1
  v*v
  v = v - 1
  v*v
  v = v - 1
  v*v
  v = v - 1
  v*v

That's a lot of work to produce 5 numbers! Python has a better way,
you'll find out how in the next section :ref:`loops`.
