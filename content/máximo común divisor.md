---
Created: 2024-06-19
aliases:
  - mcd
---
# máximo común divisor

>[!abstract] definición
>el mayor número natural que divide a dos [[números enteros]] a la vez sin dejar resto.

es decir, teniendo $a,b\in\mathbb{Z}$ y $d\in\mathbb{N}$, $d$ es el máximo común divisor o mcd de $a$ y $b$ si y sólo sí se cumple que:
$$\begin{cases}\; d\mid a\;\wedge\; d\mid b\\\; p\mid a\;\wedge\; p\mid b\;\Rightarrow p\mid d\end{cases}$$
- $d$ divide a $a$ y a $b$.
- cualquier otro número que divide a $a$ y $b$ también divide a $d$.

para hallar el mcd de dos números cualquiera, podemos usar el [[algoritmo de euclides]].