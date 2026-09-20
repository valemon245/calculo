---
Created: 2024-06-21
---
# regla de ruffini

>[!abstract] definición
>método de [[división de polinomios]], en el caso especial donde el divisor es un [[polinomio]] mónico de grado 1.

es decir, solo se puede utilizar la regla de ruffini si el divisor $Q(x)=x+b_{0}$.

siendo $gr(P)=m$ y $gr(Q)=1$, podemos decir que: 
- el grado del cociente es uno menos que el del dividendo: $gr(C)=m-1$. 
- el resto es un número: $gr(R)<1\Rightarrow gr(R)=0$. 

## aplicación de ruffini
teniendo $P(x)=a_nx^n+a_{n-1}x^{n-1}+\dots+a_2x^2+a_1x+a_0$ y $Q(x)=x+b_{0}$:

![[alg_ruffini.png]]

### observaciones
- $P(x)$ debe estar completo y ordenado.
- si $R$ es 0, podemos decir que $Q(x)$ divide a $P(x)$.
- por definición de la [[descomposición factorial de polinomios reales]] podemos decir que si $R$ es 0, $b_0$ es una [[raíz de un polinomio|raíz]] de $P(x)$.
	- también podemos usar el $C(x)$ resultante para hallar otras raíces.


## ejemplo
teniendo $P(x)=5x^4-3x^3-4x^2+6x-1$ y $Q(x)=x-2$:

![[alg_ruffini-ej.png]]
- $C(x)=5x^3+7x^2+10x+26$.
- $R(x)=51$.