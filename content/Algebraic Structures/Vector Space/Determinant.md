# Overview
The determinant is a property of a [linear operator](Linear%20Transformation.md#Linear%20Operator), defined as the factor by which area, volume or n-volume are scaled, and indicates whether the transformation preserves or reverses orientation.
# Compute the determinant
## 2-dimensional space
To compute the determinant of a linear operator on a 2-dimensional vector space, we represent it in a basis as a $2 \times 2$ matrix $T$, and define $det(T) = ad - bc$.

$\large T = \begin{bmatrix}
a & b \\
c & d 
\end{bmatrix}, \space \space \space \det(T) = ad - bc$
## 3-dimensional space
For a linear operator on a 3-dimensional vector space, its matrix representation is a $3 \times 3$ matrix:

$\large T = \begin{bmatrix}
a & b & c \\
d & e & f \\ 
g & h & i \\
\end{bmatrix}$

The determinant is:
$$\large \det(T) = a(ei-fh) - b(di - fg) + c(dh - eg)$$

#VectorSpace 