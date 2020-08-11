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

---
### VECTORS 1

**add**ress.. hm...

What if we add the following addresses:

4 Privet Dr **+** 1428 Elm St = ?

(South Park Chewbacca): "This does not make sense!"

... can't add addresses.

Everybody, please stretch your arms and point south-west
(really, do it)
(bunch of arrow pointing down-left)

You are pointing at different points, but in the same direction
Next,
Everybody, please stretch your arms and point at my nose
(really, do it)
(nose in the center of the screen)?
(Azula pointing at viewer, centered)
(other characters pointing at center of screen from different
directions)

You are pointing in different directions to the same location

So; location, direction...

- location
- direction

it feels that "location" goes with "point" and "direction"
with "vector", but reality is a bit more subtle. In fact,
the notion we want is

(- direction goes gray)
- directional instructions

ie instructions for **how to move** to a new location.

(- location and - dir.instr. get arrows pointing to point and vector)

Now, everybody take one step down, and then one step left
(GIF array of points, where each one steps down in turn, and
then left, one by one)

This is what we want; starting from different points, everyone
ended in different locations, but followed the same set of
instructions. That! is a vector.

Moreover, it IS possible to add directional instructions, as
in

first down **+** then left.

---
### VECTORS 2

When using coordinates, we write a vector as
<4,2>
and think of it as instructions to move 4 units right, and 2 up:
<4,2> = <4,0> + <0,2>

But those 4 horizontal units break down into individual **steps**
<4,2> = <4,0> + <0,2> = 4<1,0> + 2<0,1>

**Directional instructions obey the DP**!

Moreover, we can follow the instructions from **anywhere** on the plane
(previous GIF)

THAT, is what a vector is, and to remind ourselves of the difference
between point and vector, we will denote them with round and
pointy brackets respectively. Thus, if we start from different points
( (2,3)                      (4,2) )
and put the same vector on each
( (2,3) + <2,1>              (4,2) + <2,1> )
we followed the same instructions and ended in different locations
( (2,3) + <2,1> = (4,4)      (4,2) + <2,1> = (6,3) )

---
### MATRICES 1

Surprisingly, this one is easier to inderstand, because we
already did the footwork.
A matrix is a 2-dimensional array of numbers:
(
 ( 1  2  3  4
   5  6  7  8
   9 10 11 12 )
)

The dimensions are 3 by 4
(vertical 3-arrow and horiz 4-arrow)

and we read them always in that order from top to bottom and
left to right. Thus, the (2,3) entry is 7
(circled, and coords indicated)
and the (4,1) entry is 4
(erase previous; then circle, and coords indicated)

**Note** This is different from usual coordinates, and
that is just because different people decided at different times

**Note 2** In coordinates, vectors are special types of matrices
where one of the dimensions is equal to one. We have row and
column vectors
(              1
  ( 1 2 3 ) , (2)
               3
)

---
### MATRICES 2

You can add matrices coordinate-by-coordinate, and multiply them
by a scalar, also  coordinate-by-coordinate
(
 ( 1  2  3  4     ( 1 4 7 10      (  2  6 10 14
   5  6  7  8   +   2 5 8 11   =     7 11 15 19
   9 10 11 12 )     3 6 9 12 )      12 16 20 24 )
)

(
 5  ( 1  2  3  4     (  5 10 15 20
      5  6  7  8   =   25 30 35 40
      9 10 11 12 )     45 50 55 60 )
)

So that matrices also obey the DP

---
### SUMMARY

- LA is all about the DP
- numbers, vectors and matrices follow DP
- think of vectors as diretional instructions
- think of matrices as arrays of numbers


--------------------------------------------------------------------


---
### Gaussian Elimination 1

Recall one of **many** objectives in LA is to solve systems
of linear equations. First we encode the system into a matrix
(syst   ->   mtx)

Then we describe a process to automate all those horrible,
cumbersome steps we took to find the solution.

There are 3 types of "moves" we can perform on a matrix; each
changes matrix values within individual rows.

First, we can exchange two rows
(exchange system, then mtx, rows 2 & 3, flipping back and forth)

Next, we can multiply a row by a scalar
((-2) x row 1, system, then mtx, flip back-n-forth)

Finally, we can add two rows. The result substitutes one of
said rows
(blink rows 1,2, then substitute the sum, then flip b-n-f,
 syst, then mtx)

See? the system got simpler, and the matrix has more zeroes.

Continuing in this fashion, we can simplify the system by
only looking at matrix entries.

---
### Gaussian Elimination 2
