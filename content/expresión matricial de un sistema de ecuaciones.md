---
Created: 2024-06-24
aliases:
  - matriz de coeficientes
---
# expresión matricial
#ecuaciones 

>[!abstract] definición
>[[matriz|matrices]] que se pueden formar a partir de la representación general de un [[sistema de ecuaciones lineales]].

una matriz de $m$ ecuaciones con $n$ incógnitas se puede asociar con cuatro matrices por los coeficientes.
- una matriz $X$, formada por las incógnitas.
- una matriz $B$, formada por los términos independientes.
- una matriz $A'$ o $A$ extendida.

con las primeras tres podemos expresar un sistema de forma matricial de la siguiente forma:
$$\large A_{(m\times n)}\cdot X_{(n\times 1)}=B_{(m\times1)}$$

con las matrices, nos queda:
$$\begin{bmatrix}a_{11}&a_{12}&a_{13}&\dots &a_{1n} \\
a_{21}&a_{22}&a_{23}&\dots &a_{2n} \\
\vdots&\vdots&\vdots&\dots&\vdots \\
a_{m1}&a_{m2}&a_{m3}&\dots &a_{mn} \\
\end{bmatrix} \cdot
\begin{bmatrix}x_1\\x_2\\\vdots\\x_n\end{bmatrix}=
\begin{bmatrix}b_1\\b_2\\\vdots\\b_m\end{bmatrix}$$

al realizar las operaciones, vemos que:
![[alg_sistemamatricial.png]]

finalmente, la matriz $A$ extendida se logra añadiendo $B$ luego de la última columna de $A$:
$$\begin{bmatrix}
a_{11}&a_{12}&a_{13}&\dots &a_{1n}&|\;b_{1} \\
a_{21}&a_{22}&a_{23}&\dots &a_{2n}&|\;b_{2} \\
\vdots&\vdots&\vdots&\dots&\vdots&\vdots \\
a_{m1}&a_{m2}&a_{m3}&\dots &a_{mn}&|\;b_{m} \\
\end{bmatrix}_{m\times (n+1)}
$$

## relacionado
- la matriz $A'$ se usa para el [[teorema de rouché-frobenius]]. 
- las otras matrices se usan si empleamos el [[teorema de cramer]] para hallar el conjunto solución de un sistema.