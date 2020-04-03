.. _conditionals:

Conditionals
============

Learn about `if statements` in Python so that you can decide whether to
do things or not.

Look at each question and see if you can answer it, then check with
the answer we've given. Do try these out in the :ref:`repl`.

**Remember:** *understanding* is the most imporant thing, don't move
on until you really understand the question and answer.

----

You've already seen a conditional in the last section, do you remember where?

* Was it in this line of code?

::

  while v > 0:

Yes, that tests whether the variable `v` is greater than `0` and while
it is it runs the code inside the block that follows that line.

If `v = 4` what does this code do? ::

  if v < 5:
    print("small")
    print(v)
  else:
    print("large")
    print(v)

* It prints `small` followed by `4`. 

And if `v = 5` what does it do?

* It prints `large` followed by `5`.
  
If `v = 1` what does this code do? ::

  if v == 1:
    print("one")
  print("end")

* It prints `one` followed by `end`.

If `v` is any other number does it only print `end`?

* Yes, `end` is always printed because that line is not *inside* the
  body of the `if statement`.

Why do we use `==` when comparing variables and numbers?

* A single `=` means assign a value to a variable, a double `==` means
  compare two things. Python uses two different operators to avoid
  confusions. 