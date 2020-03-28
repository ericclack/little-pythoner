.. _loops:

Loops
=====

Learn about loops in Python so that you can do things many times. 

Look at each question and see if you can answer it, then check with
the answer we've given. Do try these out in the :ref:`repl`.

----

What does this do? ::

  while True:
    'I run forever!'

* It sets up a loop, that runs forever.
* The `body` of the loop is the string `'I run forever!'`
* The `body` is indented by some spaces so that Python
  knows what is `inside` the loop.
* Indentation is really imporant in Python to mark out diffent
  blocks of code. 
* The code produces the string `'I run forever!'` forever!

Do we ever see the string `'all done'`? ::

  while True:
    'I run forever!'
  'all done'


* No. That string is outside the loop, it will run once the loop
  has finished, but the loop never finishes. 
  
Does this loop finish? ::
  
  v = 5
  while v > 0:
    v*v
    v = v - 1

* I'm not sure, what does it do? 

It creates a variable `v` and it starts at `5`. While `v` is
greater than `0` we produce its square and then reduce it by `1`.

* So it does finish. And it produces: `25 16 9 4 1`.

Does this produce the same thing as the code above? ::

  for v in range(5):
    v*v

* No, but it is similar. It sets `v` to each number from `0` to `4`
  (one less than the number we give it) then produces the square.

So how do we change it to produce exactly the same sequence of squares
from 25 to 1, counting down? ::

  for v in range(5, 0, -1):
    v*v

* OK, so `range` now produces numbers from `5` down to `0`, stepping
  `-1` at a time, so going down by `1` each time.

  
