---
Created: 2024-03-29
---
# producto cartesiano

>[!abstract] definición
>el [[conjunto]] de todos los [[par ordenado|pares ordenados]] de $A$ y $B$, donde el primer elemento de cada par pertenece al conjunto $A$ y el segundo elemento pertenece al conjunto $B$.

simbólicamente, $A\times B=\left\{(x,y):x\in A \wedge y\in B\right\}$.

por ejemplo, si tenemos los conjuntos $A=\{a,b,c\}$ y $B=\{1,2\}$:
- $A\times B=\left\{\left(a,1\right),\left(a,2\right),\left(b,1\right),\left(b,2\right),\left(c,1\right),\left(c,2\right)\right\}$
- $B\times A=\left\{\left(1,a\right),\left(1,b\right),\left(1,c\right),\left(2,a\right),\left(2,b\right),\left(2,c\right)\right\}$
- $A^2=\left\{\left(a,a\right),\left(a,b\right),\left(a,c\right),\left(b,a\right),\left(b,b\right),\left(b,c\right),\left(c,a\right),\left(c,b\right),\left(c,c\right)\right\}$
- $B^2=\left\{\left(1,1\right),\left(1,2\right),\left(2,1\right),\left(2,2\right)\right\}$

también podemos hallar el producto cartesiano de conjuntos infinitos. si tenemos $C=\{ x,y,z \}$ y el conjunto $\mathbb{N}$:
- $C\times\mathbb{N}=\{(x,0),(y,0),(z,0),(x,1),(y,1),(z,1),(x,2),(y,2),(z,2),\ldots\}$

es importante saber que $A\times B$ no es lo mismo que $B\times A$, por lo que el producto cartesiano *no es conmutativo*. los pares $(x,y)$ del producto cartesiano son pares ordenados, invertir las coordenadas no los mantiene igual.

siendo ambos conjuntos finitos, si $A$ tiene un [[cardinal de un conjunto|cardinal]] de $n$ y $B$ tiene un cardinal de $m$, entonces podemos decir que $\#A\times B=n\cdot m$. 

>[!caution] importante
>está mal decir que $A\subset A\times B$ o que $B\subset A\times B$ porque los elementos de $A$ y $B$ son de distinta naturaleza a los pares ordenados que son elementos de $A\times B$.

las [[relación binaria|relaciones]] siempre son subconjuntos de un producto cartesiano.

## representación gráfica
la forma más común de representar un producto cartesiano es con un [[gráfico cartesiano]].