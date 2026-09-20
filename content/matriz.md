---
Created: 2024-06-23
---
# matriz

>[!abstract] definición
>arreglo bidimensional de elementos dispuestos de forma rectangular.

decimos que una matriz $m\times n$ tiene $m$ filas y $n$ columnas, siendo $m,n\in\mathbb{N}$. la matriz, entonces, se ve asÍ:
$$ A = \begin{gathered} [a_{ij}]_{m\times n}\\ \text{o}\\ (a_{ij})_{\substack{i=1,\dots,m\\j=1,\dots,n}} \end{gathered} = \begin{bmatrix} a_{11} & a_{12} & a_{13} & \dots & a_{1n} \\ a_{21} & a_{22} & a_{23} & \dots & a_{2n} \\ \vdots & \vdots & \vdots & \dots & \vdots \\ a_{m1} & a_{m2} & a_{m3} & \dots & a_{mn} \end{bmatrix}_{m\times n} $$

- las matrices se representan con mayúsculas, genéricamente $A$.
- los elementos de $A$ se representan con minúsculas, genéricamente $a_{ij}$.
- los subíndices $i$ y $j$ representan la fila y la columna en la que se encuentra el elemento $a$, respectivamente.
	- el máximo valor de $i$ es $m$.
	- el máximo valor de $j$ es $n$.
- $m\times n$ es la **clase** o **dimensión** de la matriz.

una matriz vive en el conjunto $\mathbb{K}^{m\times n}$, donde $\mathbb{K}$ puede ser el conjunto de los [[números racionales|racionales]], [[números reales|reales]] o [[números complejos|complejos]]. podemos definir a $\mathbb{K}^{m\times n}$ como:
$$\mathbb{K}^{m\times n}= \{ A=(a_{ij})_{\substack{i=1,\dots,m\\ j=1,\dots,m}} / a_{ij}\in\mathbb{K} \}$$
- nótese la diferencia con los elementos de la matriz, quienes pertenecen a $\mathbb{Q}$, $\mathbb{R}$ o $\mathbb{C}$.
- simbólicamente, decimos que $A\in\mathbb{K}^{m\times n}$.
	- alternativamente, $A\in \mathcal{M}_{m\times n}(\mathbb{K})$.

## clasificación
de acuerdo a la disposición o naturaleza de los elementos, podemos clasificar a las matrices.
- [[matriz cuadrada]], si $m=n$.
- matriz rectangular, si $m\neq n$.
- matriz fila, si $m=1$.
- matriz columna, si $n=1$.
- matriz nula, si $\forall i,j:a_{ij}=0$.

teniendo una matriz $A$, llamamos **matriz opuesta** de $A$ a aquella formada por todos los elementos opuestos de $A$.
- simbólicamente, $-A=[-a_{ij}]_{m\times n}$.

teniendo una matriz $A$, llamamos **matriz traspuesta** de $A$ a aquella donde sus filas son las columnas de $A$ y viceversa.
- simbólicamente, $A^{T}=[a_{ji}]_{n\times m}$.
- si una matriz es igual a su traspuesta, decimos que es una **matriz simétrica**.

### matrices especiales (cuadradas)
- [[matriz triangular]]
- [[matriz diagonal]]
- [[matriz escalar]]
- [[matriz identidad]]

### inversibilidad
una matriz cuadrada $A$ es **inversible**, regular o no singular si y sólo sí existe su [[inversa de una matriz|matriz inversa]].

## operaciones en matrices
podemos [[suma de matrices|sumar dos matrices]] si y sólo sí sus clases son iguales. decimos que son conformables para la suma.

podemos [[producto de matrices|multiplicar dos matrices]] si y sólo sí la cantidad de columnas de la primera es igual a la cantidad de filas de la segunda. 

también podemos realizar el [[producto y división de una matriz por un escalar]].

### operaciones elementales de filas
podemos realizar [[operaciones elementales de filas]] para hallar [[matrices equivalentes]] a $A$.

suele ser útil para llegar a una [[matriz escalonada]] y hallar el [[rango de una matriz]].

## relacionado
- [[combinación lineal]]
- [[dependencia e independencia lineal]]
- [[matriz adjunta de un elemento]]
- [[matriz adjunta]]
- [[determinante de una matriz]]
	- [[regla de sarrus]]
	- [[regla de laplace]]
- [[menor complementario]]
- [[cofactor]]
- un [[sistema de ecuaciones lineales]] se puede representar como una matriz.
