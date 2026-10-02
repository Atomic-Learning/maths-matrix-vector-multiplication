When a matrix is placed before a vector in a mathematical expression, it is said to operate on it, resulting in a new vector. This operation is known as matrix-vector multiplication. In order for the multiplication to be defined, the number of columns in the matrix must match the number of entries in the vector.

If we have a $m \times n$ matrix $A$ and an $n$-dimensional column vector $x$, their matrix-vector product is an $m$-dimensional column vector $b$ given by:

$$
b = Ax
$$

In component form, if $A = [a_{ij}]$ with $i = 1, \dots, m$ and $j = 1, \dots, n$, and $x = [x_j]$ with $j = 1, \dots, n$, then the entries of $b = [b_i]$ are given by:

$$
b_i = \sum_{j=1}^{n} a_{ij} x_j, \quad i = 1, \dots, m.
$$

# Example

Consider the $2 \times 3$ matrix
$$
A = \begin{bmatrix}
\ 1 & 2 & 3 \\
\ 4 & 5 & 6
\end{bmatrix}
$$
and the $3$-dimensional column vector
$$
x = \begin{bmatrix}
\ 7 \\
\ 8 \\
\ 9
\end{bmatrix}.
$$
Their matrix-vector product is the $2$-dimensional column vector
$$
b = Ax = \begin{bmatrix}
\ 1 & 2 & 3 \\
\ 4 & 5 & 6
\end{bmatrix}
\begin{bmatrix}
\ 7 \\
\ 8 \\
\ 9
\end{bmatrix}
= \begin{bmatrix}
\ 1 \times 7 + 2 \times 8 + 3 \times 9 \\
\ 4 \times 7 + 5 \times 8 + 6 \times 9
\end{bmatrix}
= \begin{bmatrix}
\ 50 \\
\ 122
\end{bmatrix}.
$$