### Why do we study Linear Algebra?

Among many other applications, to:

- Solve systems of linear equations
- Do computer graphics computations
- Solve linear programming optimization problems
- Solve eigen-problems, including
- Markov processes

Let's talk about all these

### Linear systems
are the most familiar type of problem we will face:
2x -  y +  z =  3
3x + 2y -  z = -1
 x - 3y + 2z =  2

Do you know how to find the solution? You probably
have an idea of eliminating variables; e.g., to
solve for a variable, then substitute into another
equation, then simplify, and repeat, until we find
one of the values, and then substitute to find the
others.
Let's perform that **horrible** task, just to see
what NOT to do:

The easiest way to start is to notice the positive
and negative z's in the first two equations. We decide
to eliminate z by adding these equations to get
2x -  y +  z =  3
5x +  y      =  2
 x - 3y + 2z =  2

We can also multiply the first equation by 2, and
subtract the third equation
2x -  y +  z =  3
5x +  y      =  2
3x +  y      =  4

Now the two bottom lines hold a linear system in two
equations, and we have to repeat the whole shebang.
In order to eliminate y, let's subtract line 3 from
line 2:
2x -  y +  z =  3
2x           = -2
3x +  y      =  4

We are getting somewhere! Now it is clear that x = -1.
Then, substituting this value in the third line we get
2x -  y +  z =  3
 x           = -1
3(-1) + y    =  4

or
2x -  y +  z =  3
 x           = -1
      y      =  7

Then, substituting the values for x and y in the first
line, we find
2(-1) - 7 + z =  3
 x            = -1
      y       =  7

Or, putting everything in order,
 x            = -1
      y       =  7
            z = 12

Did you follow everything? There is a handout in Canvas
waiting for you, but do not worry too much, because this
cumbersome method is useless when dealing with larger
systems; like... which line do we subtract next, and
what variable are we eliminating, and...?
There is no order or method!
**We will fix that**

### Computer graphics

https://www.youtube.com/watch?v=SMAnlPTmAwE

Linear transformations are the mathematical tool needed to

- Rotation + Translation
- Translation + Rotation
- Mirroring

But also, to keep track of
- the position and 3D-orientation of the object.
- the position and direction of the light source.
- the position, 3D-orientation, and lens aperture
  angle of the camera.

**Want to land a dream job at Pixar?**

### Eigenvectors and Markov processes

This graph represents a (slightly) simplified internet
map, with only four websites. The probability of
arriving at page A is the sum of probabilities of
- being in B and linking to A
- being in C and linking to A
- being in D and linking to A

Since each page has different numbers of links to A, (and
there are a few more pages in real life) computing these
probablilities is not fun. ** MOREOVER** the fun has just
started because we need the probabilities of arriving at
B, C, and D; and worse! We need the probabilities of arriving
at different pages **after long chains of random jumps.**

The original Google algorithm solved this by simply listing
all probabilities, and running a linear algorithm to compute
the **eigenvector** of solutions.

**Would you like to ace a class that can make you a billionaire?**

### What is Linear Algebra?

We keep talking of "linear this" and "linear that" What is the
meaning of the word linear!? Here is a baby problem for you.
You have 10 seconds to find the answer:

49 x 237  +  763 x 49  =  ?

What? You can't do that math in your head? No problem!
Collect the 49s:

49 (237 + 763) =

49    (1000)   =

  **49000**

What did we do? We used the **distributive property**

### Linear Algebra is all about the DP

Our semester-long mantra is
BOX
 Any mathematical objects that can be added and multiplied
 by scalars (i.e., numbers), and for which the addition and
 product harmonize toghether nicely in the sense of following
 the Distributive Property (DP) are object behaving **LINEARLY**
BOX

You already know all you need to know about the Linear
Algebra of plain numbers (you learned it in elementary
school).

What about the so-called linear equations? Well, we can add and
multiply:

3x + 5 = 20

3x     = 15

 x     =  5

But recall the linear system at the begining? Eliminating variables
means that we can collect them together, and that means using the
DP on variables like x,y,z (as opposed to using it on plain numbers)

This semester you will learn the mathematics of the DP, but applied
to some mathematical objects that are more involved than plain
numbers:

- Vectors
- Matrices


So...

### What is a **vector**?

and..

### What is a **matrix**?
