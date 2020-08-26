@snap[center span-100]
# **Linear Algebra**

## Math 35100

IUPUI, Fall 2020

@snapend


---
## **Rules**

@ul[list-spaced-bullets text-07]
- No homework (but see syllabus)
- No attendance (skip live session at your own risk)
- Content @fa[copyright] (to share only with classmates)
- Office hours (by appointment)
- Academic conduct (complete 1st assignment on personal integrity)
- Inclusivity (do I need to be explicit?)
- Online behavior (behave as you would in person)
@ulend


---
### **How** to study [LA]?

@snap[west]
@ul[list-spaced-bullets text-07]
- Dr Rodrigo Pérez, rperez@math.iupui.edu
- Elementary Linear Algebra, H. Anton; 11th ed.
- Homework 20%; 2 Tests (25% higher, 20% lower); Final 35%
- Complete the **Honor Code Pledge** assignment
- 50-65% **D**, 65-80% **C**, 80-90% **B**, 90-100% **A**
@ulend
@snapend

@snap[south-west fragment text-06]
www.accessengineeringlibrary.com/content/book/9781260011449


---
### **Why** study [LA]?

@snap[west]
@ul[list-spaced-bullets list-style: none text-09]
- Solve systems of **linear** equations
- Do computer graphics computations
- Solve **linear** programming optimization problems
- Solve eigen-problems, including
- Markov chain processes
@ulend
@snapend


---
### Linear Systems

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{alignat*}
\]`
@mathend
@snapend

@snap[midpoint span-50 fragment current-visible]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
      x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     5x & {}+{} &  y &&     & {}={} &  2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
     2x &&     &&     & {}={} & -2 \\
     3x & {}+{} &  y &&     & {}={} &  4
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
     3(-1) & {}+{} & y &&   & {}={} &  4
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
      x &&     &&     & {}={} & -1 \\
        &&   y &&     & {}={} &  7
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[midpoint span-50]
@math
`\[
   \begin{alignat*}{4}
     2(-1) & {}-{} & 7 & {}+{} & z & {}={} &  3 \\
      x    &&    &&    & {}={} & -1 \\
           &&  y &&    & {}={} &  7
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Linear Systems

@snap[south fragment]
*Too cumbersome!*

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
@mathend
@snapend


---
### Computer Graphics

@snap[midpoint]
[![](https://img.youtube.com/vi/SMAnlPTmAwE/0.jpg)](https://www.youtube.com/watch?v=SMAnlPTmAwE)
@snapend

@snap[south]
**Want that dream job at Pixar?**
@snapend


---
### Eigenvectors &

### Markov Processes

@snap[midpoint span-70]
@img[span-65](assets/img/Class01/googlePagerank.jpg)
@snapend

@snap[south]
**This class could make you a billionaire**
@snapend]


---
### [LA] is all about Distributivity (I)

@snap[midpoint]
@ul[list-no-bullets]
- 49 x 237  +  763 x 49  =  ?
- 49 (237 + 763) =
- 49    (1000)   =
- **49000**
@ulend
@snapend

@snap[south fragment]
The Distributive Property (or **DP**)
@snapend


---
### [LA] is all about Distributivity (II)

If some mathematical objects:

@ul
- Can be added together
- Can be multiplied by scalars (i.e., numbers)
- Obey the DP (addition and scalar product harmonize toghether)
@ulend

@snap[fragment]
Then these objects behave **linearly**
@snapend

---
### [LA] is all about Distributivity (III)

@snap[midpoint]
@ul[list-no-bullets]
- $3x + 5 = 20$
- $3x     = 15 \color{yellow}{\text{ or }} x + \tfrac{5}{3} = \tfrac{20}{3} \qquad$
- $ x     =  5$
@ulend
@snapend

@ul[south-east list-spaced-bullets]
- Numbers
- Vectors
- Matrices
- & other
@ulend


---
### What is a . . .

@snap[midpoint span-80 fragment]
![](assets/img/Class01/vector.png)
@snapend


---?image=assets/img/Class01/matrixBKGD.jpg
@snap[west]
## What is a **matrix**?
@snapend


---
### Vectors (I)

**Can addresses be added?**

@snap[west span-70 fragment]
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
**Position vs direction**

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
@ul[list-spaced-bullets]
- Location (as in *points*)
- Direction (vectors? **NO!**)
- Directional Instructions
@ulend
@snapend

@snap[east fragment span-60 text-06]
![](assets/img/Class01/dirInstrs.gif)
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

@snap[midpoint fragment]
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

**Blocks of numbers**

@snap[midpoint fragment]
@math[]
`$\begin{pmatrix}
1 &  2 &  3 & 4 \\
5 &  6 &  7 & 8 \\
9 & 10 & 11 & 12 \\
\end{pmatrix}$`
@mathend
@snapend

@snap[east fragment text-07]
@math[fragment step-fade-in-then-out]
`${\large\downarrow 3 \quad \rightarrow 4}$`
@mathend

so a

$3 \times 4$ matrix
@snapend

@snap[south fragment text-06]
@math
`$\begin{pmatrix}
1 & 2 & 3
\end{pmatrix}_{\text{this one is } 1 \times 3} \qquad
\begin{pmatrix}
1\\2\\3
\end{pmatrix}_{\text{this one is } 3 \times 1}$`
@mathend
@snapend


---
### Matrices (II)

**Adding and multiplying**

@snap[midpoint text-8]
@math
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

@snap[south fragment text-8]
@math
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
### Matrices (III)
**$\S$1.3 - Rules**

@snap[text-07]
@ol
1. $A+B = B+A$
1. $A+(B+C) = (A+B)+C$
1. $A(BC) = (AB)C$
1. $A(B+C) = AB + AC$
1. $(A+B)C = AC + BC$
1. $s(B+C) = sB + sC$
1. $(s+t)C = sC + tC$
1. $s(tC) = (st)C$
1. $s(BC) = (sB)C$
1. $A+0 = 0+A = A$
1. $A+(-1)A = A-A = 0$
1. $0A = A0 = 0$
1. $sA = 0$ means that either $s=0$ or $A=0$
@olend
@snapend

---
### Matrices (IV)

**$\S$1.4 - Inverses**

@ul[list-no-bullets text-07]
- $A \cdot A^{-1} = A^{-1} \cdot A = I$
- $(A \cdot B) \cdot (B^{-1} \cdot A^{-1}) = A \cdot (B \cdot B^{-1}) \cdot A^{-1} = A \cdot I \cdot A^{-1} = A \cdot A^{-1} = I$
- i.e., $(A \cdot B)^{-1} = B^{-1} \cdot A^{-1}$
- $A^n = A \cdot \ldots \cdot A$, and $A^{-n} = (A^{-1})^n = A^{-1} \cdot \ldots \cdot A^{-1}$
- $A^r \cdot A^s = A^{r+s}$ and $(A^r)^s = A^{rs}$
- If $k \neq 0$ and $A$ is invertible, then
- $\circ\quad (A^{-1})^{-1} = A$,
- $\circ\quad (A^n)^{-1} = A^{-n} = (A^{-1})^n$, and
- $\circ\quad (kA)^{-1} = \tfrac{1}{k}A^{-1}$
- $(kA) \cdot (\tfrac{1}{k}A^{-1}) = \tfrac{1}{k} (kA) \cdot A^{-1} = (\tfrac{1}{k} k) A \cdot A^{-1} = (1)I = I$
- i.e., $(kA)^{-1} = \tfrac{1}{k}A^{-1}$
@ulend

@snap[south-east fragment text-07]
@math
`\[
  \begin{pmatrix}a&b\\c&d\end{pmatrix}^{-1} = \dfrac{1}{ad-bc} \begin{pmatrix}d&-b\\-c&a\end{pmatrix}
\]`
@mathend
@snapend


---
### Matrices (V)

**$\S$1.4 - Transposes**

@snap[south fragment text-08]
@math
`\[
  \begin{pmatrix}1&2&3&4\\5&6&7&8\\9&10&11&12\end{pmatrix}^T = \begin{pmatrix}1&5&9\\2&6&10\\3&7&11\\4&8&12\end{pmatrix}
\]`
@mathend
@snapend

@ul[list-no-bullets text-07]
- $(A^T)^T = A$
- $(A + B)^T = A^T + B^T$
- $(kA)^T = kA^T$
- $(A \cdot B)^T = B^T \cdot A^T$
- $(A^T)^{-1} = (A^{-1})^T$
@ulend


---
### Summary 1

@ul[list-spaced-bullets]
- **[LA]** is all about Distributivity
- Numbers, vectors, and matrices are distributive, which is why these are the objects studied in [LA]
- Think of vectors as *directional instructions*
- Think of matrices as blocks of numbers with meaning...
- ... but also with arithmetic properties (including a multiplicative inverse), and a transpose operation
@ulend


---
### Gaussian Elimination (I)
**$\S$1.2**

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{alignat*}{4}
    \phantom{-}
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
     x & {}-{} & 3y & {}+{} & 2z & {}={} &  2
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    \phantom{-}
    2 & -1 &  1 &  \color{blue}{3} \\
    3 &  2 & -1 & \color{blue}{-1} \\
    1 & -3 &  2 &  \color{blue}{2}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[{\ }{\ }
  \begin{alignat*}{4}
    \phantom{-}
     x & {}-{} & 3y & {}+{} & 2z & {}={} &  2 \\
    3x & {}+{} & 2y & {}-{} &  z & {}={} & -1 \\
    2x & {}-{} &  y & {}+{} &  z & {}={} &  3
  \end{alignat*}
  \longrightarrow
  \begin{pmatrix}
    \phantom{-}
    1 & -3 &  2 &  \color{blue}{2} \\
    3 &  2 & -1 & \color{blue}{-1} \\
    2 & -1 &  1 &  \color{blue}{3}
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
    -2 &  6 & -4 & \color{blue}{-4} \\
     3 &  2 & -1 & \color{blue}{-1} \\
     2 & -1 &  1 &  \color{blue}{3}
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
    -2 & 6 &        -4 & \color{blue}{-4} \\
     3 & 2 &        -1 & \color{blue}{-1} \\
     0 & \phantom{-} 5 & -3 & \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Gaussian Elimination (II)
**$\S$1.2**

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    2 & -1 &  1 &  \color{blue}{3} \\
    3 &  2 & -1 & \color{blue}{-1} \\
    1 & -3 &  2 &  \color{blue}{2}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    3 &  2 & -1 & \color{blue}{-1} \\
    2 & -1 &  1 &  \color{blue}{3}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    0 & 11 & -7 & \color{blue}{-7} \\
    2 & -1 &  1 &  \color{blue}{3}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    0 & 11 & -7 & \color{blue}{-7} \\
    0 &  5 & -3 & \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east color-red fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    0 &  1 & \tfrac{-7}{11} & \color{blue}{\tfrac{-7}{11}} \\
    0 &  5 & -3 & \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    0 & 11 & -7 & \color{blue}{-7} \\
    0 &  5 & -3 & \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & -3 &  2 &  \color{blue}{2} \\
    0 &  1 & -1 & \color{blue}{-5} \\
    0 &  5 & -3 & \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & \color{blue}{-13} \\
    0 & 1 & -1 &  \color{blue}{-5} \\
    0 & 5 & -3 &  \color{blue}{-1}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & \color{blue}{-13} \\
    0 & 1 & -1 &  \color{blue}{-5} \\
    0 & 0 &  2 &  \color{blue}{24}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 & -1 & \color{blue}{-13} \\
    0 & 1 & -1 &  \color{blue}{-5} \\
    0 & 0 &  1 &  \color{blue}{12}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 0 &  0 &  \color{blue}{-1} \phantom{3} \\
    0 & 1 & -1 &  \color{blue}{-5} \\
    0 & 0 &  1 &  \color{blue}{12}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in]
`\[
  \begin{pmatrix}
    1 & 0 & 0 &  \color{blue}{-1} \\
    0 & 1 & 0 &   \color{blue}{7} \\
    0 & 0 & 1\phantom{-} &  \color{blue}{12}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
\begin{alignat*}{4}
    x & &   & &   & {}={} & -1 \\
      & & y & &   & {}={} &  7 \\
      & &   & & z & {}={} &  12
  \end{alignat*}
\qquad
  \begin{pmatrix}
    1 & 0 & 0 &  \color{blue}{-1} \\
    0 & 1 & 0 &   \color{blue}{7} \\
    0 & 0 & 1\phantom{-} &  \color{blue}{12}
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Reduced Row Echelon Form

**$\S$1.2 - (in short, RREF)**

@snap[midpoint fragment current-visible text-08]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    0 & 1 & 0 & {\color{yellow}{*}} & {\color{yellow}{*}} & 0 & {\color{yellow}{*}} & 0 & 0 & {\color{yellow}{*}} \\
    0 & 0 & 1 & {\color{yellow}{*}} & {\color{yellow}{*}} & 0 & {\color{yellow}{*}} & 0 & 0 & {\color{yellow}{*}} \\
    0 & 0 & 0 & 0                   & 0                   & 1 & {\color{yellow}{*}} & 0 & 0 & {\color{yellow}{*}} \\
    0 & 0 & 0 & 0                   & 0                   & 0 & 0                   & 1 & 0 & {\color{yellow}{*}} \\
    0 & 0 & 0 & 0                   & 0                   & 0 & 0                   & 0 & 1 & {\color{yellow}{*}} \\
    0 & 0 & 0 & 0                   & 0                   & 0 & 0                   & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-08]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    0 & 1 & 0 & \color{yellow}{2} & \color{yellow}{5} & 0 & \color{yellow}{0} & 0 & 0 & \color{yellow}{2} \\
    0 & 0 & 1 & \color{yellow}{1} & \color{yellow}{0} & 0 & \color{yellow}{4} & 0 & 0 & \color{yellow}{1} \\
    0 & 0 & 0 & 0                 & 0                 & 1 & \color{yellow}{3} & 0 & 0 & \color{yellow}{0} \\
    0 & 0 & 0 & 0                 & 0                 & 0 & 0                 & 1 & 0 & \color{yellow}{7} \\
    0 & 0 & 0 & 0                 & 0                 & 0 & 0                 & 0 & 1 & \color{yellow}{6} \\
    0 & 0 & 0 & 0                 & 0                 & 0 & 0                 & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Systems with many solutions (I)
**$\S$1.2**

@snap[east fragment current-visible]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1 & 2\phantom{-} & 3\phantom{-} &  8 \\
    4 & 5            & 6            & 23 \\
    7 & 8            & 9            & 38\phantom{-}
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
    7 &  8 &  9 & 38\phantom{-}
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

@snap[east fragment]
@math
`\[
  \begin{pmatrix}
    1 & 0\phantom{-} & -1 &  2 \\
    0 & 1            &  2 &  3 \\
    0 & 0            &  0 &  0\phantom{-}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[west fragment]
@math
`\[
   \begin{alignat*}{4}
      x & {}+{} & 2y & {}+{} & 3z & {}={} & 0 \\
     4x & {}+{} & 5y & {}+{} & 6z & {}={} & 0 \\
     7x & {}+{} & 8y & {}+{} & 9z & {}={} & 0
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[south-west fragment]
@math
`\[
   \begin{alignat*}{4}
      x & {} {} &   & {}-{} &  z & {}={} & 2 \\
        & {} {} & y & {}+{} & 2z & {}={} & 3 \\
      0 & {}+{} & 0 & {}+{} &  0 & {}={} & 0
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[south fragment]
@math
`\[\qquad
   \begin{alignat*}{4}
      x & {}={} & 2 -   {\color{blue}{t}} \\
      y & {}={} & 3 - 2 {\color{blue}{t}} \\
      z & {}={} &       {\color{blue}{t}}
   \end{alignat*}
  \]`
@mathend
@snapend


---
### Systems with many solutions (II)
**$\S$1.2**

@snap[west text-07]
@math[]
`\[
  \begin{pmatrix}
    0 & {\color{yellow}{1}} & 0 & 2 & 5 & 0 & 0 & 0 & 0 & 2 \\
    0 & 0 & {\color{yellow}{1}} & 1 & 0 & 0 & 4 & 0 & 0 & 1 \\
    0 & 0 & 0 & 0 & 0 & {\color{yellow}{1}} & 3 & 0 & 0 & 0 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & {\color{yellow}{1}} & 0 & 7 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & {\color{yellow}{1}} & 6 \\
    0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} &  \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &  \\
      x_4 & {}={} &  \\
      x_5 & {}={} &  \\
      x_6 & {}={} &  \\
      x_7 & {}={} &  \\
      x_8 & {}={} &  \\
      x_9 & {}={} &  \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &   \\
      x_4 & {}={} &   \\
      x_5 & {}={} &   \\
      x_6 & {}={} &   \\
      x_7 & {}={} &   \\
      x_8 & {}={} &   \\
      x_9 & {}={} &   \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} &   \\
      x_6 & {}={} &   \\
      x_7 & {}={} &   \\
      x_8 & {}={} &   \\
      x_9 & {}={} &   \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} & c \\
      x_6 & {}={} &   \\
      x_7 & {}={} & d \\
      x_8 & {}={} &   \\
      x_9 & {}={} &   \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} & c \\
      x_6 & {}={} &   \\
      x_7 & {}={} & d \\
      x_8 & {}={} &   \\
      x_9 & {}={} & 6 \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} & a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &   \\
      x_4 & {}={} & b \\
      x_5 & {}={} & c \\
      x_6 & {}={} &   \\
      x_7 & {}={} & d \\
      x_8 & {}={} & 7 \\
      x_9 & {}={} & 6 \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} &   a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &     \\
      x_4 & {}={} &   b \\
      x_5 & {}={} &   c \\
      x_6 & {}={} & -3d \\
      x_7 & {}={} &   d \\
      x_8 & {}={} &   7 \\
      x_9 & {}={} &   6 \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
   \begin{alignat*}{4}
      x_1 & {}={} &   a \\
      x_2 & {}={} & \phantom{2-2b-5c} \\
      x_3 & {}={} &  1-b-4d \\
      x_4 & {}={} &   b \\
      x_5 & {}={} &   c \\
      x_6 & {}={} & -3d \\
      x_7 & {}={} &   d \\
      x_8 & {}={} &   7 \\
      x_9 & {}={} &   6 \\
   \end{alignat*}
  \]`
@mathend
@snapend

@snap[east fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
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
@mathend
@snapend


---
### Elementary Matrices (I)
**$\S$1.5**

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1 & 4 & 7 & 10 \\
    2 & 5 & 8 & 11 \\
    3 & 6 & 9 & 12
  \end{pmatrix}
  =
  \begin{pmatrix}
    1 & 4 & 7 & 10 \\
    {\color{yellow}{3}} & {\color{yellow}{6}} & {\color{yellow}{9}} & {\color{yellow}{12}} \\
    {\color{green}{2}} & {\color{green}{5}} & {\color{green}{8}} & {\color{green}{11}}
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    {\color{yellow}{-5}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1 & 4 & 7 & 10 \\
    2 & 5 & 8 & 11 \\
    3 & 6 & 9 & 12
  \end{pmatrix}
  =
  \begin{pmatrix}
    {\color{green}{5}} & {\color{green}{20}} & {\color{green}{35}} & {\color{green}{50}} \\
    2 &  5 &  8 & 11 \\
    3 &  6 &  9 & 12
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{3}}\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1 & 4 & 7 & 10 \\
    2 & 5 & 8 & 11 \\
    3 & 6 & 9 & 12
  \end{pmatrix}
  =
  \begin{pmatrix}
     1 &  4 &  7 & 10 \\
    {\color{green}{11}} & {\color{green}{23}} & {\color{green}{35}} & {\color{green}{47}} \\
     3 &  6 &  9 & 12
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Elementary Matrices (II)
**$\S$1.5 Invertibility**

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
\phantom{  \cdot
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
\phantom{  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&0&{\color{yellow}{1}}\\0&{\color{yellow}{1}}&0
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
\]`
@mathend
@snapend


@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    {\color{yellow}{-5}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
\phantom{  \cdot
  \begin{pmatrix}
    {\color{yellow}{\tfrac{-1}{5}}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    {\color{yellow}{-5}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    {\color{yellow}{\tfrac{-1}{5}}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
\phantom{  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    {\color{yellow}{-5}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    {\color{yellow}{\tfrac{-1}{5}}}&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
\]`
@mathend
@snapend


@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{3}}\\0&0&1
  \end{pmatrix}
\phantom{  \cdot
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{-3}}\\0&0&1
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment current-visible text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{3}}\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{-3}}\\0&0&1
  \end{pmatrix}
\phantom{  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix} }
\]`
@mathend
@snapend

@snap[midpoint fragment text-07]
@math[fragment step-fade-in-then-out]
`\[
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{3}}\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&1&{\color{yellow}{-3}}\\0&0&1
  \end{pmatrix}
  =
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&0&1
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[south span-80 fragment text-08]
** Theorem 1.5.2** Every elementary matrix is invertible,
and the inverse is also an elementary matrix


---
### Elementary Matrices (III)
**$\S$1.5** Revisit Elimination

@snap[midpoint text-04]
@math
`\[
  \begin{pmatrix}
    1 & 0 & -1 &  2 \\
    0 & 1 &  2 &  3 \\
    0 & 0 &  0 &  0
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    1 &  0 &  -1 &   2 \\
    0 &  1 &   2 &   3 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    1 &  2 &   3 &   8 \\
    0 &  1 &   2 &   3 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    1 &  2 &   3 &   8 \\
    0 & -3 &  -6 &  -9 \\
    0 & -6 & -12 & -18
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    1 &  2 &  3 &  8 \\
    0 & -3 & -6 & -9 \\
    7 &  8 &  9 & 38
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    1 & 2 & 3 &  8 \\
    4 & 5 & 6 & 23 \\
    7 & 8 & 9 & 38
  \end{pmatrix}
{\color{blue}{\leftarrow}}
  \begin{pmatrix}
    4 & 5 & 6 & 23 \\
    1 & 2 & 3 &  8 \\
    7 & 8 & 9 & 38
  \end{pmatrix}
\]`
@mathend
@snapend

@snap[south fragment text-05]
@math
`\[
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&{\color{yellow}{6}}&1
  \end{pmatrix}
  \qquad\quad
  \begin{pmatrix}
    1&{\color{yellow}{-2}}&0\\0&1&0\\0&0&1
  \end{pmatrix}
  \qquad\quad
  \begin{pmatrix}
    1&0&0\\0&{\color{yellow}{\tfrac{-1}{3}}} &0\\0&0&1
  \end{pmatrix}
  \qquad\quad
  \begin{pmatrix}
    1&0&0\\0&1&0\\{\color{yellow}{-7}}&0&1
  \end{pmatrix}
  \qquad\quad
  \begin{pmatrix}
    1&0&0\\{\color{yellow}{-4}}&1&0\\0&0&1
  \end{pmatrix}
  \qquad\quad
  \begin{pmatrix}
    0&{\color{yellow}{1}}&0\\{\color{yellow}{1}}&0&0\\0&0&1
  \end{pmatrix}
\]`
@mathend
@snapend


---
### Elementary Matrices (IV)
**$\S$1.5 Row Operations as Matrix Multiplication**

@snap[midpoint fragment text-05]
@math
`\[
  \begin{pmatrix} 1&0&0\\0&1&0\\0&6&1 \end{pmatrix}
  \cdot
  \begin{pmatrix} 1&-2&0\\0&1&0\\0&0&1 \end{pmatrix}
  \cdot
  \begin{pmatrix} 1&0&0\\0&\tfrac{-1}{3} &0\\0&0&1 \end{pmatrix}
  \cdot
  \begin{pmatrix} 1&0&0\\0&1&0\\-7&0&1 \end{pmatrix}
  \cdot
  \begin{pmatrix} 1&0&0\\-4&1&0\\0&0&1 \end{pmatrix}
  \cdot
  \begin{pmatrix} 0&1&0\\1&0&0\\0&0&1 \end{pmatrix}
  \cdot
  \begin{pmatrix}
    \color{yellow}{4} & \color{yellow}{5} & \color{yellow}{6} & \color{yellow}{23} \\
    \color{yellow}{1} & \color{yellow}{2} & \color{yellow}{3} &  \color{yellow}{8} \\
    \color{yellow}{7} & \color{yellow}{8} & \color{yellow}{9} & \color{yellow}{38}
  \end{pmatrix}
  =
  \begin{pmatrix}
    \color{blue}{1} & \color{blue}{0} & \color{blue}{-1} &  \color{blue}{2} \\
    \color{blue}{0} & \color{blue}{1} &  \color{blue}{2} &  \color{blue}{3} \\
    \color{blue}{0} & \color{blue}{0} &  \color{blue}{0} &  \color{blue}{0}
  \end{pmatrix}
\]`
@mathend
@snapend

@ul[south list-no-bullets text-08]
- $E_6 \cdot E_5 \cdot E_4 \cdot E_3 \cdot E_2 \cdot E_1 \cdot \color{yellow}{A} = \color{blue}{R}$
- ${\ }$
- $\color{yellow}{A} = E_1^{-1} \cdot E_2^{-1} \cdot E_3^{-1} \cdot E_4^{-1} \cdot E_5^{-1} \cdot E_6^{-1} \cdot \color{blue}{R}$
- ${\ }$
xs@ulend
@snapend


---
### Elementary Matrices (V)
**$\S$1.5 Row Operations as Matrix Multiplication**

@snap[midpoint text-05]
@math
`\[{\color{blue}{\leftarrow}} \begin{pmatrix}\color{yellow}{1}&\color{yellow}{-3}&\color{yellow}{2}\\\color{yellow}{0}&\color{yellow}{1}&\color{yellow}{-1}\\\color{yellow}{0}&\color{yellow}{5}&\color{yellow}{-3}\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&-3&2\\0&11&-7\\0&5&-3\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&-3&2\\0&11&-7\\2&-1&1\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&-3&2\\3&2&-1\\2&-1&1\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}2&-1&1\\3&2&-1\\1&-3&2\end{pmatrix}\]`

<br />
`\[\begin{pmatrix}1&0&0\\0&1&0\\0&0&1\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&0&0\\0&1&-1\\0&0&1\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&0&-1\\0&1&-1\\0&0&1\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&0&-1\\0&1&-1\\0&0&2\end{pmatrix} {\color{blue}{\longleftarrow}} \begin{pmatrix}1&0&-1\\0&1&-1\\0&5&-3\end{pmatrix}{\color{blue}{\leftarrow}}\]`
@mathend
@snapend


---



@snap[midpoint fragment text-05]
@math
`\[
  \begin{pmatrix}
    1&0&0\\0&1&0\\0&6&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&-2&0\\0&1&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&\tfrac{-1}{3} &0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\0&1&0\\-7&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    1&0&0\\-4&1&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    0&1&0\\1&0&0\\0&0&1
  \end{pmatrix}
  \cdot
  \begin{pmatrix}
    \color{yellow}{4} & \color{yellow}{5} & \color{yellow}{6} & \color{yellow}{23} \\
    \color{yellow}{1} & \color{yellow}{2} & \color{yellow}{3} &  \color{yellow}{8} \\
    \color{yellow}{7} & \color{yellow}{8} & \color{yellow}{9} & \color{yellow}{38}
  \end{pmatrix}
  =
  \begin{pmatrix}
    \color{blue}{1} & \color{blue}{0} & \color{blue}{-1} &  \color{blue}{2} \\
    \color{blue}{0} & \color{blue}{1} &  \color{blue}{2} &  \color{blue}{3} \\
    \color{blue}{0} & \color{blue}{0} &  \color{blue}{0} &  \color{blue}{0}
  \end{pmatrix}
\]`
@mathend
@snapend

























---

---?image=assets/img/thatsAllFolks.jpg

---