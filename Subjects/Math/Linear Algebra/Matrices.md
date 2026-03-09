[[Math MOC]]
[[Math Linear Algebra Home]]

A Matrix is a rectangular array of numbers, (refert to 2d array in python)



A Matrix may look like this:
$$
\begin{pmatrix}1 \ 2\\
1  \ 1  \\ 
1 \ 2 \\
1 \ 3 \\

\end{pmatrix}
$$
### Order of matrix

The order of a matrix may be expressed as m x n
where m is the number of rows in the matrix
and n is the number of columns in the matrix
### Matrix equality
Let $$
A= \begin{pmatrix}
a \ b \\ 
c \ d
 \end{pmatrix}
$$
And 
$$
B= \begin{pmatrix}
e \ f \\
g \ h \\

\end{pmatrix}
$$

**A** is only equal to **B** iff:
$$
a = e, b=f, c=g,d=h
$$
- The order of the matrix has to be the same
### Matrix addition

Using the same matrices of A and B from above:
$$
A+B= \begin{pmatrix}
a+e  &  b+f  \\
c+g  &  h+d
\end{pmatrix}

$$

### Matrix multiplication

$$
A \times B = \begin{pmatrix}
ae +bg  & af+bh \\
ce+dg & cf+dh \\
\end{pmatrix}
$$
Uhh get it?

Looks like you dont, so lets walk through it slowly...

#### Go through the rows of the Left matrix, top to bottom, and for each row go through a column from left to rigth in the right matrix

so..
$$
A_{row_{1}}= \begin{pmatrix}
a & b
\end{pmatrix}

$$
$$
B_{col_{1}}= \begin{pmatrix}
e \\
g
\end{pmatrix}
$$
In each row and coloumn you selected, go through the elements one at a time simultaneosly, and multiply both of the elements,
$$
a \times e
$$
$$
b \times g
$$
Sum these products, an you get your first element of your resultant matrix!
Repeat until done


