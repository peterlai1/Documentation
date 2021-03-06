# Avg

\begin{equation}
A = \begin{bmatrix}
    -1 & 2          \\\\
    3 & -4
\end{bmatrix}, 
B = \begin{bmatrix}
     2 & 4          \\\\
      6 & 8
\end{bmatrix}, 
C = \begin{bmatrix}
    -1 \\\\
      3
\end{bmatrix}, 
D = \begin{bmatrix}
    -1 & 3
\end{bmatrix}
\end{equation}

### Avg(Scalar) = ERROR

\begin{equation}
Avg(-1) = ERROR
\end{equation}

> [!CAUTION]
> If executed with a scalar it will throw an exception.

### Avg(Vector) = Scalar

The orientation of the vector will be maintained in the resulting vector.

\begin{equation}
Avg(C) = 1
\end{equation}

### Avg(Matrix) = Scalar

\begin{equation}
Avg(A) = 0
\end{equation}
