---
Created: 2024-05-20
aliases:
  - variación simple
  - disposición simple
---
# arreglo, variación o disposición simple
#matematica 

>[!abstract] definición
>siendo $n\leqslant m$, todos los grupos distintos que se pueden formar tal que:
>- cada grupo está formado por $n$ elementos distintos de los $m$ dados.
>- dos grupos son distintos solo si difieren en sus elementos o en el orden de los mismos. 

concepto dentro del [[análisis combinatorio]]. $A_{n}^{m}$ se lee “arreglos simples de los $m$ elementos de un conjunto tomados de a $n$”.
- otras notaciones: $A_{n,m}$, $A_{m}^{n}$, $V_{n}^{m}$, $D_{n}^{m}$ 
- *el orden es importante en los arreglos*. cuando el orden de los elementos no es relevante, usamos una [[combinación simple]]. 
- si $m=n$, es mejor usar una [[permutación simple]].

a diferencia del [[arreglo con repetición]], los elementos no se pueden repetir. si tenemos $m$ elementos y se desea formar combinaciones de $n$ elementos distintos:
- el primer lugar tiene $m$ posibilidades.
- el segundo lugar tiene $(m-1)$ posibilidades por cada una de las anteriores
- el tercer lugar tiene $(m-2)$ posibilidades, y así hasta llegar al último lugar.
- en el último lugar, como ya se usaron $(n-1)$ de los elementos, podemos decir que quedan $m-(n-1)$ posibilidades por cada una de las anteriores.

hay una relación entre un arreglo $A_{n}^{m}$ y la [[función factorial]]. esa relación es:
$$m! =\underbrace{m\cdot(m-1)\cdot(m-2)\cdot\dots\cdot(m-n+1)}_{\Huge\textcolor{red}{A_n^m \text{ (cuando } m\neq n\text{)}}}\cdot\underbrace{(m-n)\cdot(m-n-1)\cdot\dots\cdot3\cdot2\cdot1}_{\Huge\textcolor{blue}{ (m-n)!}}$$

por lo tanto, podemos decir que:
$$\large m!=A_n^m\cdot(m-n)! \;\;\Rightarrow\;\; A_n^m=\frac{m!}{(m-n)!}$$

***

en la calculadora, podemos calcular un arreglo usando la tecla `nPr`:
![[alg_calculadora-nPr.png|350]]