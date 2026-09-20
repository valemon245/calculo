---
Created: 2024-06-21
---
# división de polinomios

>[!abstract] definición
>división de dos [[polinomio|polinomios]].

teniendo los polinomios $P(x)$ y $Q(x)$, podemos aplicar el [[algoritmo de la división]] y decir que existen un $C(x)$ y un $R(x)$ únicos tal que:
$$P(x)=C(x)\cdot Q(x)+R(x), \quad R(x)=0\vee gr(R)<gr(Q)$$
- $P(x)$ es el dividendo,
- $Q(x)$ es el divisor,
- $C(x)$ es el cociente,
- $R(x)$ es el resto,
- $gr()$ es el grado de un polinomio.

siendo $gr(P)=m$ y $gr(Q)=n$, podemos decir que: 
- $m<n\Rightarrow C(x)=0\wedge R(x)=P(x)$. 
- $m\geq n\Rightarrow gr(C)=m-n \wedge gr(R)\leq n-1$. 

si el resto de dividir $P$ por $Q$ es 0, decimos que $Q(x)$ es divisor de $P(x)$.

## ruffini
si el divisor $Q(x)$ es un polinomio mónico de grado 1, podemos dividir usando la [[regla de ruffini]].

en este caso especial, también podemos afirmar que $Q(x)=x-a$ divide a $P(x)$ si y sólo sí $P(a)=0$. ver [[teorema del resto]].
