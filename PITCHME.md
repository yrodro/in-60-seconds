@snap[center span-100]
# **Linear Algebra**

## Math 35100

IUPUI, Fall 2020

@snapend


---
### **How** will we study Linear Algebra?

@snap[midpoint span-90]
@ul[list-spaced-bullets list-style: none text-09]
- Dr Rodrigo Pérez, rperez@math.iupui.edu
- Elementary Linear Algebra, H. Anton; 11th ed.
- Assignments 20%; 3 Exams 30% each; Final 20%
- 50-65% **D**, 65-80% **C**, 80-90% **B**, 90-100% **A**
@ulend @snapend


---
@snap[north span-80]
### **Why** do we study Linear Algebra?
@snapend

@snap[south span-70]
@ul[list-spaced-bullets list-style: none text-09]
- Solve systems of linear equations
- Do computer graphics computations
- Solve linear programming optimization problems
- Solve eigen-problems, including
- Markov chain processes
@ulend @snapend


---
@snap[north span-80]
## Linear Systems
@snapend

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{align*}
\]`
@mathend@snapend

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{align*}
  \]`
@mathend@snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{align*}
  \]`
@mathend @snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     2x &&     &&     & {}={} & -2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{align*}
  \]`
@mathend @snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
     3(-1) & {}+{} & y &&   & {}={} &  4
   \end{align*}
  \]`
@mathend @snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
        &&   y &&     & {}={} &  7
   \end{align*}
  \]`
@mathend @snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
     2(-1) & {}-{} & 7 & {}+{} & z & {}={} &  3 \\
      x    &&    &&    & {}={} & -1 \\
           &&  y &&    & {}={} &  7
   \end{align*}
  \]`
@mathend @snapend


---
@snap[north span-80]
Linear Systems
@snapend

@snap[south fragment]
**We will fix that...**
@snapend

@snap[midpoint span-50]
@math
`\[
   \begin{align*}
      x &&     &&      & {}={} & -1 \\
        &&   y &&      & {}={} &  7 \\
        &&     &&    z & {}={} & 12
   \end{align*}
  \]`
@mathend @snapend




---
@snap[north span-80]
### Computer graphics
@snapend

@snap[midpoint]
[![](https://img.youtube.com/vi/SMAnlPTmAwE/0.jpg)](https://www.youtube.com/watch?v=SMAnlPTmAwE)
@snapend

@snap[south span-80 fragment]
**Want to land a dream job at Pixar?**
@snapend


---
@snap[north span-80]
### Eigenvectors and Markov processes
@snapend

@snap[midpoint span-65]
@img[span-65](assets/img/Class01/googlePagerank.jpg)
@snapend

@snap[south fragment span-80]
**Would you like to ace a class that can make you a billionaire?**
@snapend]


---
@snap[north span-80]
### **What** is Linear Algebra?
@snapend

@snap[midpoint span-70]
@ul[list-no-bullets none text-09]
- 49 x 237  +  763 x 49  =  ?
- 49 (237 + 763) =
- 49    (1000)   =
- **49000**
@ulend@snapend

@snap[south span-80 fragment]
The **Distributive Property** (or DP)
@snapend


---
@snap[north span-80]
### Linear Algebra is all about the DP
@snapend

@snap[midpoint span-65]
@quote[]
  If some mathematical objects can be added and multiplied
  by scalars (i.e., numbers), and if the addition and product
  harmonize toghether nicely in the sense of following the (DP),
  then these objects are behaving **LINEARLY**
@snapend


---
@snap[north span-80]
### **What** is Linear Algebra?
@snapend

@snap[midpoint span-70]
@ul[list-no-bullets list-style: none text-09]
- $3x + 5 = 20$
- $3x     = 15$
- $ x     =  5$
@ulend@snapend

@snap[south span-60]
@ul[list-spaced-bullets list-style: none text-09]
- Vectors
- Matrices
@ulend@snapend


---
### What is a ...

@snap[midpoint span-80 fragment]
![](assets/img/Class01/vector.png)
@snapend


---?image=assets/img/Class01/matrixBKGD.jpg
@snap[north span-80]
### What is a **matrix**?
@snapend


---
### Vectors

1428 Elm Street + 4 Privet Drive

@snap[south-west span-20]
![](assets/img/Class01/elmSt.jpg)
@snapend

@snap[south-east span-20]
![](assets/img/Class01/privetDr.jpg)
@snapend

@snap[north-east span-20]
![](assets/img/Class01/chewbacca.jpg)
@snapend
It does not make sense!


---
@snap[north]
### Vectors 1
@snapend
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
@snap[north]
### Vectors 2
@snapend
@snap[west]
@ul[list-no-bullets none text-09]
- Location (points)
- Direction (vectors?)
- Directional Instructions
@ulend
@snapend

@snap[east fragment span-60]
![](assets/img/Class01/dirInstrs.gif)
@snapend

@snap[south fragment]
1 step down **+** 1 step left
@snapend


---
@snap[north]
### Vectors 3
@snapend

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

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) \phantom{+ \langle 2,1 \rangle = (4,4)} \qquad (4,2) \phantom{+ \langle 2,1 \rangle = (6,3)}$`
@mathend
@snapend

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) + \langle 2,1 \rangle \phantom{= (4,4)} \qquad (4,2) + \langle 2,1 \rangle \phantom{= (6,3)}
$`
@mathend
@snapend

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$(2,3) + \langle 2,1 \rangle = (4,4) \qquad (4,2) + \langle 2,1 \rangle = (6,3)$`
@mathend
@snapend


---
### Matrices 1

@snap[midpoint fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\begin{pmatrix}
1 &  2 &  3 & 4 \\
5 &  6 &  7 & 8 \\
9 & 10 & 11 & 12 \\
\end{pmatrix}$`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\downarrow 3 \qquad \rightarrow 4$`
@mathend
@snapend

@snap[south fragment current-visible]
@math[fragment step-fade-in-then-out]
`$\begin{pmatrix}
1 & 2 & 3
\end{pmatrix} \qquad
\begin{pmatrix}
1\\2\\3
\end{pmatrix}$`
@mathend
@snapend


---
### Matrices 2

@snap[midpoint span-30 fragment current-visible] 
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

@snap[south span-30 fragment current visible]
@math[fragment step-fade-in-then-out]
`5
$\begin{pmatrix}
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
- **LA** is all about the **DP**.
- Numbers, vectors, and matrices obey the DP.
- Think of vectors as *directional instructions*.
- Think of matrices as arrays of numbers with meaning.
@ulend @snapend


---
### Gaussian Elimination 1

@snap[west span-20 fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{align*}
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
    x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
  \end{align*}
  \longrightarrow
  \begin{pmatrix}
    2 & -1 & 1 &  3 \\
    3 &  2 & 1 & -1 \\
    1 &  3 & 2 &  2
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west span-20 fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{align*}
    x & {}-{} & 3y & {}+{} & 2z & {}={} &  2 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3
  \end{align*}
  \longrightarrow
  \begin{pmatrix}
    1 &  3 & 2 &  2 \\
    3 &  2 & 1 & -1 \\
    2 & -1 & 1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west span-20 fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{align*}
    -2x & {}+{} & 6y & {}-{} & 4z & {}={} & -4 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3
  \end{align*}
  \longrightarrow
  \begin{pmatrix}
    -2 &  6 & -4 & -4 \\
     3 &  2 &  1 & -1 \\
     2 & -1 &  1 &  3
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west span-20 fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{align*}
    -2x & {}+{} & 6y & {}-{} & 4z & {}={} & -4 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
        & {}+{} & 5y & {}-{} & 3z & {}={} & -1
  \end{align*}
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
### Gaussian Elimination 2

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 color-red fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[east span-50 fragment current-visible]
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

@snap[south-east fragment span-50 color-blue current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{align*}
    x & &   & &   & {}={} & -1 \\
      & & y & &   & {}={} &  7 \\
      & &   & & z & {}={} &  12
  \end{align*}
\]`
@mathend
@snapend





---
@snap[midpoint span-100]
![](assets/img/thatsAllFolks.jpg)
@snapend
