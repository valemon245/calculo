---
Created: 2024-04-21
aliases:
  - productoria
  - productorio
---
# notación productoria
#matematica 

>[!abstract] definición
>notación matemática que representa el producto de una sucesión de números.

simbólicamente, se representa con una letra pi mayúscula: $\prod$.

la notación productoria tiene la siguiente estructura:
$$\Large\prod_{\textcolor{yellow}{i=\textcolor{orange}{1}}}^{\textcolor{red}{n}}\textcolor{blue}{a_{\textcolor{yellow}{i}}}=\textcolor{blue}{a_{\textcolor{orange}{1}}\cdot a_{\textcolor{yellow}{2}}\cdot a_{\textcolor{yellow}{3}}\cdot \dots \cdot a_{\textcolor{red}{n}}}$$
- lo que se halla al lado del sigma es *lo que se multiplica*. en este caso, $\textcolor{blue}{a_{\textcolor{yellow}{i}}}$.
	- usamos $\textcolor{blue}{a_{\textcolor{yellow}{i}}}$ para aclarar que el producto se realiza una vez por cada valor posible de $\textcolor{yellow}{i}$, incluso si $\textcolor{yellow}{i}$ no está presente en el término que se está multiplicando. 
		- a $\textcolor{yellow}{i}$ se le llama **índice**.
- lo que se halla arriba y debajo sel sigma nos indica *dónde comienza y termina la serie de valores que estamos multiplicando*:
	- abajo tenemos que $\textcolor{yellow}{i=\textcolor{orange}{1}}$, por lo que nuestro primer $\textcolor{yellow}{i}$ va a tener el valor de $\textcolor{orange}{1}$. desde ahí, seguimos escalando dentro del conjunto de los [[números naturales]].
		- a $\textcolor{orange}{1}$ se le llama **límite inferior**.
	- arriba tenemos a $\textcolor{red}{n}$, significa que la operación se acaba cuando $\textcolor{yellow}{i}$ tiene el valor de $\textcolor{red}{n}$.
		- a $\textcolor{red}{n}$ se le llama **límite superior**, y debe ser un número natural.
- esta operación se lee como “productoria de $a_{i}$ con $i$ variando de $1$ a $n$”.

## relacionado
- un concepto muy similar es la [[notación sumatoria]].
- la [[función factorial]] se puede ver como una productoria en la mayoría de casos.
