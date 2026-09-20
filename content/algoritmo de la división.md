---
Created: 2024-06-10
---

>[!abstract] definición
>teorema que asegura que la división entre [[números enteros]] es posible.

teniendo $a,b\in\mathbb{Z}$ donde $b\neq 0$, podemos asociarlos a un $q,r\in\mathbb{Z}$ únicos tal que:
$$a=b\cdot q+r, \text{ siendo } 0 \leqslant r \;\textless \;|b|$$
- $a$ es el **dividendo**,
- $b$ es el **divisor**,
- $q$ es el **cociente**,
- y $r$ es el **resto**.

si el resto de dividir $a$ por $b$ es 0, podemos decir que $b$ divide a $a$: [[divisibilidad de los enteros]].

la división euclidiana es la base del [[algoritmo de euclides]].

## ejemplo
tenemos $a=-236$ y $b=27$.
- $-236=27\cdot(-8)+(-20)$ ❌ 
	- técnicamente nos da el resultado deseado, pero no cumple con la condición de que $r\geqslant 0$.
- $-236=27\cdot(-9)+7$ ✅

