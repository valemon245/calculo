---
Created: 2024-06-24
---
# regla de sarrus

>[!abstract] definición
>fórmula para hallar el [[determinante de una matriz]] de orden 3.

teniendo una [[matriz]] cuadrada de orden 3, podemos usar la regla de sarrus para calcular el determinante.

lo que hacemos es sumar los productos de los elementos de $A$ en las diagonales principales, y luego restarle los productos de los elementos de $A$ en las diagonales secundarias.

es ideal expandir la matriz para darnos una idea más visual, agregando las primeras dos filas (o columnas) al final de la matriz. entonces, los cálculos son:
![[alg_sarrus.png]]

$$\large |A|=
\begin{align}
&(a_{11}\cdot a_{22}\cdot a_{33}+a_{21}\cdot a_{32}\cdot a_{13}+a_{31}\cdot a_{12}\cdot a_{23}) \\
&-(a_{13}\cdot a_{22}\cdot a_{31}+a_{23}\cdot a_{32}\cdot a_{11}+a_{33}\cdot a_{12}\cdot a_{21})
\end{align}$$
