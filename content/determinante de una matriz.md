---
Created: 2024-06-24
aliases:
  - determinante
---
# determinante de una matriz

>[!abstract] definición
>[[función]] que asigna un número o escalar a una [[matriz cuadrada]] a partir de sus elementos.

teniendo una [[matriz]] $A$, el determinante es una función de $\mathbb{K}^{n\times n}\to \mathbb{K}$ y se define dependiendo del orden de nuestra matriz.

si $n=1$, decimos que:
$$\large |\;|:\mathbb{K}^{1\times 1}\to \mathbb{K}/|A| = |a_{11}| = a_{11}$$

si $n=2$, decimos que:
$$\large |\;|:\mathbb{K}^{2\times 2}\to \mathbb{K}/|A| = \begin{vmatrix}a_{11}&a_{12}\\a_{21}&a_{22}\end{vmatrix} = a_{11}\cdot a_{22}-a_{12}\cdot a_{21}$$

- es decir, $|A|$ es igual a la resta de los productos de los elementos en las diagonales de la matriz.

si $n\geq 3$, decimos que:
$$\large |\;|:\mathbb{K}^{n\times n}\to \mathbb{K}/|A| = \sum_{j=1}^n a_{ij}\cdot (-1)^{i+j}\cdot \Big|A_{(i,j)}\Big|,\;\;con\:1\leq i\leq n$$

- ver [[regla de laplace]].
- si $n=3$, también podemos usar la [[regla de sarrus]].

## propiedades
- el determinante de una matriz es 0 si:
	- la matriz tiene dos filas o columnas iguales.
	- la matriz tiene dos o más filas/columnas [[dependencia e independencia lineal|linealmente dependientes]].
	- la matriz tiene filas proporcionales.
	- la matriz tiene una fila o columna nula.
- el determinante del producto entre dos matrices es igual al producto de los determinantes de esas matrices: $|A\cdot B| = |A|\cdot |B|$.
- el determinante de una [[matriz triangular]] o [[matriz diagonal|diagonal]] es igual al producto de los elementos de la diagonal principal.
	- simbólicamente, $|A|=\prod_{i=1}^na_{ii}=a_{11}\cdot a_{22}\cdot\dots\cdot a_{nn}$.
- el determinante de la [[matriz identidad]] siempre es 1.
- si se multiplica un escalar no nulo por una fila o columna de una matriz, el determinante de la matriz inicial se multiplica por el escalar.
- si se intercambian dos filas columnas de una matriz, el determinante cambia de signo.
- el determinante de una matriz es igual al de su traspuesta.

## por qué determinante?
el determinante de una matriz tiene varios usos:
- hallar la solución de un [[sistema de ecuaciones lineales]]. ver [[regla de cramer]].
- hallar la [[inversa de una matriz]]. si el determinante es 0, sabemos que una matriz no es inversible.
