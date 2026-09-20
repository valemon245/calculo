---
Created: 2024-06-24
aliases:
  - matriz inversa
  - inversa
---
# inversa de una matriz

>[!abstract] definición
>teniendo una [[matriz cuadrada]] $A$, otra [[matriz]] de la misma clase tal que, multiplicada por $A$, de como resultado la [[matriz identidad]] de esa clase.

decimos que una matriz $A$ es **inversible** si y sólo sí $\exists A^{-1}/A\cdot A^{-1}=A^{-1}\cdot A=I_n$.

por propiedades de la [[determinante de una matriz]], podemos decir que $A_{n\times n}$ es inversible si y sólo sí su [[rango de una matriz|rango]] es igual a $n$, lo que a su vez implica que su determinante es distinto de 0.

***

digamos que queremos hallar la matriz $X$ tal que:
$$ A\cdot X=B$$

si hablaramos de números, podríamos dividir $A$ en ambas partes de la igualdad y despejar $X$. sin embargo, *no se puede dividir entre matrices*.

aquí es donde radica la importancia de la matriz inversa, ya que multiplicar $A$ por su inversa logra el mismo efecto que “dividir” por $A$. 

entonces, nos quedaría:
$$\begin{gather}
A\cdot X=B  \\
X=B\cdot A^{-1}
\end{gather}
$$

este concepto es clave para el [[teorema de cramer]].

## cómo hallar la inversa de una matriz
teniendo una matriz $A$ inversible, su inversa es igual a la [[matriz adjunta]] de $A$ dividida por el determinante de $A$.
$$ A^{-1}=\frac{Adj(A)}{|A|}$$

