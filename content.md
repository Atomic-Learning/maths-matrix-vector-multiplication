When a matrix is placed before a vector in a mathematical expression, it is said to operate on it, resulting in a new vector. This operation is known as matrix-vector multiplication. 

# Validity

In order for the multiplication to be defined, the number of columns in the matrix must match the number of entries in the vector.

# Definition

If we have a $m \times n$ matrix $A$ and an $n$-dimensional column vector $x$, their matrix-vector product is an $m$-dimensional column vector $b$ given by:

$$
b = Ax
$$

In component form, if $A = [a_{ij}]$ with $i = 1, \dots, m$ and $j = 1, \dots, n$, and $x = [x_j]$ with $j = 1, \dots, n$, then the entries of $b = [b_i]$ are given by:

$$
b_i = \sum_{j=1}^{n} a_{ij} x_j, \quad i = 1, \dots, m.
$$

# Example

Consider the $2 \times 3$ matrix:

$$
A = \begin{bmatrix}
{\color{#0072B2} 1} & {\color{#0072B2} 2} & {\color{#0072B2} 3} \\
{\color{#D55E00} 4} & {\color{#D55E00} 5} & {\color{#D55E00} 6}
\end{bmatrix}
$$

and the $3$-dimensional column vector

$$
x = \begin{bmatrix}
{\color{#009E73} 7} \\
{\color{#E69F00} 8} \\
{\color{#CC79A7} 9}
\end{bmatrix}.
$$

Their matrix-vector product is the $2$-dimensional column vector $b$

$$
b &= Ax \\
&= \begin{bmatrix}
{\color{#0072B2} 1} & {\color{#0072B2} 2} & {\color{#0072B2} 3} \\
{\color{#D55E00} 4} & {\color{#D55E00} 5} & {\color{#D55E00} 6}
\end{bmatrix}
\begin{bmatrix}
{\color{#009E73} 7} \\
{\color{#E69F00} 8} \\
{\color{#CC79A7} 9}
\end{bmatrix}\\
&= \begin{bmatrix}
{\color{#0072B2} 1} \times {\color{#009E73} 7} + {\color{#0072B2} 2} \times {\color{#E69F00} 8} + {\color{#0072B2} 3} \times {\color{#CC79A7} 9} \\
{\color{#D55E00} 4} \times {\color{#009E73} 7} + {\color{#D55E00} 5} \times {\color{#E69F00} 8} + {\color{#D55E00} 6} \times {\color{#CC79A7} 9}
\end{bmatrix}\\
&= \begin{bmatrix}
{\color{#0072B2} 50} \\
{\color{#D55E00} 122}
\end{bmatrix}.
$$