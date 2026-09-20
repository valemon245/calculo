---
Created: 2024-06-24
---
# regla de cramer

>[!abstract] definición
>teorema que dice que la solución para cada incógnita $x_j$ de un [[sistema crameriano]] se pueden hallar como un cociente tal que:
>- el dividendo es el [[determinante de una matriz|determinante]] de la [[expresión matricial de un sistema de ecuaciones|matriz de coeficientes]] pero reemplazando la $j$-ésima columna con los términos independientes.
>- el divisor es el determinante de la matriz del sistema.

podemos definir la regla de cramer como:
$$x_{1}=\frac{\begin{vmatrix}b_{1}&a_{12}&\dots&a_{1n}\\b_{2}&a_{22}&\dots&a_{2n}\\\vdots&\vdots&\dots&\vdots\\b_{m}&a_{m2}&\dots&a_{mn}\end{vmatrix}}{|A|}\quad x_{2}=\frac{\begin{vmatrix}a_{11}&b_{1}&\dots&a_{1n}\\a_{21}&b_{2}&\dots&a_{2n}\\\vdots&\vdots&\dots&\vdots\\a_{m1}&b_{m}&\dots&a_{mn}\end{vmatrix}}{|A|}
\quad\dots\quad
x_{m}=\frac{\begin{vmatrix}a_{11}&a_{12}&\dots&b_{1}\\a_{21}&a_{22}&\dots&b_{2}\\\vdots&\vdots&\dots&\vdots\\a_{m1}&a_{m2}&\dots&b_{m}\end{vmatrix}}{|A|}
$$

el sistema debe ser crameriano (matriz de coeficientes [[inversa de una matriz|inversible]]) porque el determinante de $A$ no puede ser 0.