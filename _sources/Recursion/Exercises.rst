..  Copyright (C)  Brad Miller, David Ranum
    This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/.

:skipreading:`True`

Programming Exercises
---------------------

#. Write a recursive function to compute the factorial of a number.

#. Write a recursive function to reverse a list.

#. Modify the recursive tree program using one or all of the following
   ideas:

   -  Modify the thickness of the branches so that as the ``branch_len``
      gets smaller, the line gets thinner.

   -  Modify the color of the branches so that as the ``branch_len`` gets
      very short it is colored like a leaf.

   -  Modify the angle used in turning the turtle so that at each branch
      point the angle is selected at random in some range. For example,
      choose an angle between 15 and 45 degrees. Play around to see
      what looks good.

   -  Modify the ``branch_len`` recursively so that instead of always
      subtracting the same amount you subtract a random amount in some
      range.

   If you implement all of the above ideas you will have a very
   realistic looking tree.

#. Find or invent an algorithm for drawing a fractal mountain. Hint: one
   approach to this uses triangles again.

#. Write a recursive function to compute the Fibonacci sequence. How
   does the performance of the recursive function compare to that of an
   iterative version?

#. Implement a solution to the Tower of Hanoi using three stacks to keep
   track of the disks.

#. Using the ``turtle`` graphics module, write a recursive program to
   display a Hilbert curve.

#. Using the ``turtle`` graphics module, write a recursive program to
   display a Koch snowflake.

#. Write a program to solve the following problem. You have two jugs: a
   4-gallon jug and a 3-gallon jug. Neither of the jugs have markings on
   them. There is a pump that can be used to fill the jugs with water.
   How can you get exactly two gallons of water in the 4-gallon jug?

#. Generalize the problem above so that the parameters to your solution
   include the sizes of each jug and the final amount of water to be
   left in the larger jug.

#. Write a program that solves the following problem. Three missionaries
   and three cannibals come to a river and find a boat that holds two
   people. Everyone must get across the river to continue on the
   journey. However, if the cannibals ever outnumber the missionaries on
   either bank, the missionaries will be eaten. Find a series of
   crossings that will get everyone safely to the other side of the
   river.

#. Modify the Tower of Hanoi program using ``turtle`` graphics to animate
   the movement of the disks. Hint: you can make multiple turtles and
   have them shaped like rectangles.

#. Pascal’s triangle is a number triangle with numbers arranged in
   staggered rows such that

   .. math::
      a_{nr} = {n! \over{r! (n-r)!}}

   This is the equation for a binomial coefficient. You can
   build Pascal’s triangle by adding the two numbers that are diagonally
   above a number in the triangle. An example of Pascal’s triangle is
   shown below.

   ::

                         1
                       1   1
                     1   2   1
                   1   3   3   1
                 1   4   6   4   1

   Write a program that prints out Pascal’s triangle. Your program
   should accept a parameter that tells how many rows of the triangle to
   print.

#. Suppose you are a computer scientist/art thief who has broken into a
   major art gallery. All you have with you to haul out your stolen art
   is your knapsack which only holds :math:`W` pounds of art, but for
   every piece of art you know its value and its weight. Write a dynamic
   programming function to help you maximize your profit. Here is a
   sample problem for you to get started: suppose your knapsack
   can hold a total weight of 20 pounds. You have 5 items as follows:

   ::

        item     weight      value
          1        2           3
          2        3           4
          3        4           8
          4        5           8
          5        9          10

#. This problem is called the string edit distance problem, and is quite
   useful in many areas of research. Suppose that you want to transform
   the word *algorithm* into the word *alligator*. For each letter you
   can either copy the letter from one word to another at a cost of 5,
   you can delete a letter at cost of 20, or insert a letter at a cost
   of 20. The total cost to transform one word into another is used by
   spell-check programs to provide suggestions for words that are close
   to one another. Use dynamic programming techniques to develop an
   algorithm that gives you the smallest edit distance between any two
   words.

