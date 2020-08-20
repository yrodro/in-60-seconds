@snap[center span-100]
# **Linear Algebra**

## Math 35100

IUPUI, Fall 2020

@snapend


---
### **Rules**

@snap[midpoint span-90]
@ul[list-spaced-bullets list-style: none text-09]
- No homework
- No attendance
- No shared content
- Office hours
- Academic conduct
- Inclusivity
- Online behavior
@ulend @snapend


---
### **How** will we study [LA]?

@snap[midpoint span-90]
@ul[list-spaced-bullets list-style: none text-09]
- Dr Rodrigo Pérez, rperez@math.iupui.edu
- Elementary Linear Algebra, H. Anton; 11th ed.
- Assignments 20%; 3 Exams 30% each; Final 20%
- 50-65% **D**, 65-80% **C**, 80-90% **B**, 90-100% **A**
@ulend @snapend


---
### **Why** do we study [LA]?

@snap[south span-70]
@ul[list-spaced-bullets list-style: none text-09]
- Solve systems of **linear** equations
- Do computer graphics computations
- Solve **linear** programming optimization problems
- Solve eigen-problems, including
- Markov chain processes
@ulend @snapend


---
## Linear Systems

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{alignat*}
\]`
@mathend@snapend

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{alignat*}
  \]`
@mathend@snapend


---
Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{alignat*}
  \]`
@mathend @snapend


---
Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     2x &&     &&     & {}={} & -2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{alignat*}
  \]`
@mathend @snapend


---
Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
     3(-1) & {}+{} & y &&   & {}={} &  4
   \end{alignat*}
  \]`
@mathend @snapend


---
Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
        &&   y &&     & {}={} &  7
   \end{alignat*}
  \]`
@mathend @snapend


---
Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2(-1) & {}-{} & 7 & {}+{} & z & {}={} &  3 \\
      x    &&    &&    & {}={} & -1 \\
           &&  y &&    & {}={} &  7
   \end{alignat*}
  \]`
@mathend @snapend


---
Linear Systems

@snap[south fragment]
**We will fix that...**
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
      x &&     &&      & {}={} & -1 \\
        &&   y &&      & {}={} &  7 \\
        &&     &&    z & {}={} & 12
   \end{alignat*}
  \]`
@mathend @snapend


---
### Computer graphics

@snap[midpoint]
[![](https://img.youtube.com/vi/SMAnlPTmAwE/0.jpg)](https://www.youtube.com/watch?v=SMAnlPTmAwE)
@snapend

@snap[south span-80]
**Want that dream job at Pixar?**
@snapend


---
### Eigenvectors and Markov processes

@snap[midpoint span-65]
@img[span-65](assets/img/Class01/googlePagerank.jpg)
@snapend

@snap[south span-80]
**This class could make you a billionaire**
@snapend]


---
### **What** is [LA]?

@snap[midpoint span-70]
@ul[list-no-bullets none text-09]
- 49 x 237  +  763 x 49  =  ?
- 49 (237 + 763) =
- 49    (1000)   =
- **49000**
@ulend@snapend

@snap[south span-50 fragment]
The **Distributive Property** (or DP)
@snapend


---
### [LA] is all about Distributivity

@snap[midpoint span-80]
If some mathematical objects satisfy:
@ul[list-spaced-bullets list-style: none text-09]
- They can be added together
- They can be multiplied by scalars (i.e., numbers)
- The addition and scalar product harmonize toghether (they obey the DP)
@ulend
then these objects behave **Linearly**
@snapend


---
### **What** is [LA]?

@snap[midpoint span-70]
@ul[list-no-bullets list-style: none text-09]
- $3x + 5 = 20$
- $3x     = 15$
- $ x     =  5$
@ulend@snapend

@ul[south list-spaced-bullets list-style: none text-09]
- Vectors
- Matrices
@ulend


---
### What is a ...

@snap[midpoint span-80 fragment]
![](assets/img/Class01/vector.png)
@snapend


---?image=assets/img/Class01/matrixBKGD.jpg
@snap[south span-80]
## What is a **matrix**?
@snapend


---
### Vectors (I)

@snap[west span-70]
1428 Elm Street + 4 Privet Drive
@snapend

@snap[south-west span-30]
![](assets/img/Class01/elmSt.jpg)
@snapend

@snap[south span-40]
![](assets/img/Class01/privetDr.jpg)
@snapend

@snap[south-east fragment span-30]
![](assets/img/Class01/chewbacca.jpg)

It does not make sense!
@snapend



---
### Vectors (II)

@snap[midpoint fragment span-70 fragment step-fade-in-then-out]
![](assets/img/Class01/crowdPointing.jpg)
@snapend
@snap[midpoint fragment]
![](assets/img/Class01/azula.jpg)
@snapend
@snap[south fragment span-30]
![](assets/img/Class01/idiot.png)
@snapend
@snap[west fragment span-25]
![](assets/img/Class01/alladin.gif)
@snapend
@snap[south-east fragment span-25]
![](assets/img/Class01/mario.png)
@snapend
@snap[south-west fragment span-30]
![](assets/img/Class01/homer.gif)
@snapend
@snap[east fragment span-25]
![](assets/img/Class01/regular.gif)
@snapend
@snap[north-east fragment span-30]
![](assets/img/Class01/spongebob.png)
@snapend


---
### Vectors (III)

@snap[west]
@ul[list-spaced-bullets list-style: none text-09]
- Location (as in *points*)
- Direction (vectors?) **NO!**
- Directional Instructions
@ulend
@snapend

@snap[east fragment span-60]
![](assets/img/Class01/dirInstrs.gif)
@snapend

@snap[south-east fragment]
1 step down **+** 1 step left
@snapend


---
### Vectors (IV)

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\langle 4,2 \rangle \phantom{ = \langle 4,0 \rangle + \langle 0,2 \rangle = 4 \langle 1,0 \rangle + 2 \langle 0,1 \rangle}$`
@mathend
@snapend

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\langle 4,2 \rangle = \langle 4,0 \rangle + \langle 0,2 \rangle  \phantom{ = 4 \langle 1,0 \rangle + 2 \langle 0,1 \rangle}$`
@mathend
@snapend

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\langle 4,2 \rangle = \langle 4,0 \rangle + \langle 0,2 \rangle = 4 \langle 1,0 \rangle + 2 \langle 0,1 \rangle$`
@mathend
@snapend

@snap[south fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) \phantom{+ \langle 2,1 \rangle = (4,4)} \qquad (4,2) \phantom{+ \langle 2,1 \rangle = (6,3)}$`
@mathend
@snapend

@snap[south fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) + \langle 2,1 \rangle \phantom{= (4,4)} \qquad (4,2) + \langle 2,1 \rangle \phantom{= (6,3)}
$`
@mathend
@snapend

@snap[south fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) + \langle 2,1 \rangle = (4,4) \qquad (4,2) + \langle 2,1 \rangle = (6,3)$`
@mathend
@snapend


---
### Matrices (I)

@snap[midpoint fragment]
@math[]
`$\begin{pmatrix}
1 &  2 &  3 & 4 \\
5 &  6 &  7 & 8 \\
9 & 10 & 11 & 12 \\
\end{pmatrix}$`
@mathend
@snapend

@snap[east fragment]
@math[fragment step-fade-in-then-out]
`$\downarrow 3 \quad \rightarrow 4$`
@mathend

so a

$3 \times 4$ matrix
@snapend

@snap[south]
@math[fragment]
`$\begin{pmatrix}
1 & 2 & 3
\end{pmatrix} \qquad
\begin{pmatrix}
1\\2\\3
\end{pmatrix}$`
@mathend
@snapend


---
### Matrices (II)

@snap[midpoint fragment current-visible] 
@math[fragment step-fade-in-then-out]
`$\begin{pmatrix}
1 &  2 &  3 & 4 \\
5 &  6 &  7 & 8 \\
9 & 10 & 11 & 12 \\
\end{pmatrix} +
\begin{pmatrix}
1 & 4 & 7 & 10 \\
2 & 5 & 8 & 11 \\
3 & 6 & 9 & 12 \\
\end{pmatrix} =
\begin{pmatrix}
 2 &  6 & 10 & 14 \\
 7 & 11 & 15 & 19 \\
12 & 16 & 20 & 24 \\
\end{pmatrix}$`
@mathend
@snapend

@snap[south fragment current visible]
@math[fragment step-fade-in-then-out]
`$ 5
\begin{pmatrix}
1 &  2 &  3 & 4 \\
5 &  6 &  7 & 8 \\
9 & 10 & 11 & 12 \\
\end{pmatrix} =
\begin{pmatrix}
 5 & 20 & 35 & 50 \\
10 & 25 & 40 & 55 \\
15 & 30 & 45 & 60 \\
\end{pmatrix}$`
@mathend
@snapend


---
### Summary 1

@snap[midpoint span-70]
@ul[list-spaced-bullets list-style: none text-09]
- **[LA]** is all about Distributivity
- Numbers, vectors, and matrices are distributive
- Think of vectors as *directional instructions*
- Think of matrices as arrays of numbers with meaning
@ulend @snapend


---
### Gaussian Elimination (I)

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
    x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    2 & -1 & 1 &  3 \\
    3 &  2 & 1 & -1 \\
    1 &  3 & 2 &  2
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    x & {}-{} & 3y & {}+{} & 2z & {}={} &  2 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    1 &  3 & 2 &  2 \\
    3 &  2 & 1 & -1 \\
    2 & -1 & 1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    -2x & {}+{} & 6y & {}-{} & 4z & {}={} & -4 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    -2 &  6 & -4 & -4 \\
     3 &  2 &  1 & -1 \\
     2 & -1 &  1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    -2x & {}+{} & 6y & {}-{} & 4z & {}={} & -4 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
        &&        5y & {}-{} & 3z & {}={} & -1
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    -2 & 6 & -4 & -4 \\
     3 & 2 &  1 & -1 \\
     0 & 5 & -3 & -1
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Gaussian Elimination (II)

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    2 & -1 &  1 &  3 \\
    3 &  2 & -1 & -1 \\
    1 & -3 &  2 &  2
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    3 &  2 & -1 & -1 \\
    2 & -1 &  1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    0 & 11 & -7 & -7 \\
    2 & -1 &  1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    0 & 11 & -7 & -7 \\
    0 &  5 & -3 & -1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east color-red fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    0 &  1 & \tfrac{-7}{11} & \tfrac{-7}{11} \\
    0 &  5 & -3 & -1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    0 & 11 & -7 & -7 \\
    0 &  5 & -3 & -1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  2 \\
    0 &  1 & -1 & -5 \\
    0 &  5 & -3 & -1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & -13 \\
    0 & 1 & -1 &  -5 \\
    0 & 5 & -3 &  -1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & -13 \\
    0 & 1 & -1 &  -5 \\
    0 & 0 &  2 &  24
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & -13 \\
    0 & 1 & -1 &  -5 \\
    0 & 0 &  1 &  12
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 &  0 &  -1 \\
    0 & 1 & -1 &  -5 \\
    0 & 0 &  1 &  12
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & 0 &  -1 \\
    0 & 1 & 0 &   7 \\
    0 & 0 & 1 &  12
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[south-east fragment color-blue current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    x & &   & &   & {}={} & -1 \\
      & & y & &   & {}={} &  7 \\
      & &   & & z & {}={} &  12
  \end{alignat*}
\]`
@mathend
@snapend


---
### Reduced Row Echelon Form (**RREF**)

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    0 & 1 & 0 & * & * & 0 & * & 0 & 0 & * \\
    0 & 0 & 1 & * & * & 0 & * & 0 & 0 & * \\
    0 & 0 & 0 & 0 & 0 & 1 & * & 0 & 0 & * \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & * \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & * \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    0 & 1 & 0 & 2 & 5 & 0 & 0 & 0 & 0 & 2 \\
    0 & 0 & 1 & 1 & 0 & 0 & 4 & 0 & 0 & 1 \\
    0 & 0 & 0 & 0 & 0 & 1 & 3 & 0 & 0 & 0 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 7 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 6 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend


---
Systems with many solutions (I)

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 2 & 3 &  8 \\
    4 & 5 & 6 & 23 \\
    7 & 8 & 9 & 38
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 &  2 &  3 &  8 \\
    0 & -3 & -6 & -9 \\
    7 &  8 &  9 & 38
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 &  2 &   3 &   8 \\
    0 & -3 &  -6 &  -9 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 &  2 &   3 &   8 \\
    0 &  1 &   2 &   3 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 &  0 &  -1 &   2 \\
    0 &  1 &   2 &   3 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 &  2 \\
    0 & 1 &  2 &  3 \\
    0 & 0 &  0 &  0
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x & {}+{} & 2y & {}+{} & 3z & {}={} & 0 \\
     4x & {}+{} & 5y & {}+{} & 6z & {}={} & 0 \\
     7x & {}+{} & 8y & {}+{} & 9z & {}={} & 0
   \end{alignat*}
  \]`
@mathend @snapend

@snap[south-west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x & {} {} &   & {}-{} &  z & {}={} & 2 \\
        & {} {} & y & {}+{} & 2z & {}={} & 3 \\
      0 & {}+{} & 0 & {}+{} &  0 & {}={} & 0
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[south-east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x & {}={} & 2 -   {\color{green}t} \\
      y & {}={} & 3 - 2 {\color{green}t} \\
      z & {}={} &       {\color{green}t}
   \end{alignat*}
  \]`
@mathend @snapend


---
### Systems with many solutions (II)

@snap[west text-07]
@math[]
`\[
  \begin{pmatrix}
    0 & 1 & 0 & 2 & 5 & 0 & 0 & 0 & 0 & 2 \\
    0 & 0 & 1 & 1 & 0 & 0 & 4 & 0 & 0 & 1 \\
    0 & 0 & 0 & 0 & 0 & 1 & 3 & 0 & 0 & 0 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 7 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 6 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[south-east span-50]
@math
`\[
   \begin{alignat*}{4}
      x_1 & {}={} &  \\
      x_2 & {}={} &  \\
      x_3 & {}={} &  \\
      x_4 & {}={} &  \\
      x_5 & {}={} &  \\
      x_6 & {}={} &  \\
      x_7 & {}={} &  \\
      x_8 & {}={} &  \\
      x_9 & {}={} &  \\
   \end{alignat*}
  \]`
@mathend @snapend

@snap[south-east span-50]
@math
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} &   \\
      x_3 & {}={} &   \\
      x_4 & {}={} &   \\
      x_5 & {}={} &   \\
      x_6 & {}={} &   \\
      x_7 & {}={} &   \\
      x_8 & {}={} &   \\
      x_9 & {}={} &   \\
   \end{alignat*}
  \]`
@mathend @snapend

@snap[south-east span-50]
@math
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} &   \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} & c \\
      x_6 & {}={} &   \\
      x_7 & {}={} & d \\
      x_8 & {}={} &   \\
      x_9 & {}={} &   \\
   \end{alignat*}
  \]`
@mathend @snapend

@snap[south-east span-50]
@math
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} &   \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} & c \\
      x_6 & {}={} &   \\
      x_7 & {}={} & d \\
      x_8 & {}={} &   \\
      x_9 & {}={} & 6 \\
   \end{alignat*}
  \]`
@mathend @snapend

@snap[south-east span-50]
@math
`\[
   \begin{alignat*}{4}
      x_1 & {}={} &   a \\
      x_2 & {}={} &  2-2b-5c \\
      x_3 & {}={} &  1-b-4d \\
      x_4 & {}={} &   b \\
      x_5 & {}={} &   c \\
      x_6 & {}={} & -3d \\
      x_7 & {}={} &   d \\
      x_8 & {}={} &   7 \\
      x_9 & {}={} &   6 \\
   \end{alignat*}
  \]`
@mathend @snapend









---?image=assets/img/thatsAllFolks.jpg

