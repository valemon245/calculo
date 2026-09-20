---
Created: 2024-06-24
---
# matriz adjunta de un elemento
#matrices 

>[!abstract] definición
>teniendo una [[matriz cuadrada]] $A$ de orden $n$ con un elemento $a_{ij}$, la submatriz de orden $n-1$ que se obtiene al eliminar la $i$-ésima fila y la $j$-ésima columna de $A$.

simbólicamente, podemos representarla como $A_{(i,j)}$.
- no confundir con $A_{ij}$, que representa el [[cofactor]] del elemento.

si calculamos el [[determinante de una matriz|determinante]] de $A_{(i,j)}$, obtenemos el [[menor complementario]] de $a_{ij}$.

## ejemplo
$$A=\begin{bmatrix}a_{11}&a_{12}&a_{13}&a_{14}\\a_{21}&a_{22}&a_{23}&a_{24}\\a_{31}&a_{32}&a_{33}&a_{34}\\a_{41}&a_{42}&a_{43}&a_{44}\end{bmatrix}_{4\times 4}A_{(2,3)}=\begin{bmatrix}a_{11}&a_{12}&a_{14}\\a_{31}&a_{32}&a_{34}\\a_{41}&a_{42}&a_{44}\end{bmatrix}_{3\times 3}$$