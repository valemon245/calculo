---
Created: 2024-04-21
aliases:
  - sigma
  - sumatoria
  - sumatorio
---
# sumatoria
#matematica 

>[!abstract] definición
>notación matemática que representa la suma de una sucesión de números.

simbólicamente, se representa usando la letra sigma mayúscula: $\sum$.

la notación sumatoria tiene la siguiente estructura:
$$\sum_{\textcolor{yellow}{i=\textcolor{orange}{1}}}^{\textcolor{red}{n}}\textcolor{blue}{a_{\textcolor{yellow}{i}}}=\textcolor{blue}{a_{\textcolor{orange}{1}}+a_{\textcolor{yellow}{2}}+a_{\textcolor{yellow}{3}}+\dots +a_{\textcolor{red}{n}}}$$
- lo que se halla al lado del sigma es *lo que se suma*. en este caso, $\textcolor{blue}{a_{\textcolor{yellow}{i}}}$.
	- usamos $\textcolor{blue}{a_{\textcolor{yellow}{i}}}$ para aclarar que la suma se realiza una vez por cada valor posible de $\textcolor{yellow}{i}$, incluso si $\textcolor{yellow}{i}$ no está presente en el término que se está sumando. 
		- a $\textcolor{yellow}{i}$ se le llama **índice**.
- lo que se halla arriba y debajo del sigma nos indica *dónde comienza y termina la serie de valores que estamos sumando*:
	- abajo tenemos que $\textcolor{yellow}{i=\textcolor{orange}{1}}$, por lo que nuestro primer $\textcolor{yellow}{i}$ va a tener el valor de $\textcolor{orange}{1}$. desde ahí, seguimos escalando dentro del conjunto de los [[números naturales]].
		- a $\textcolor{orange}{1}$ se le llama **límite inferior**.
	- arriba tenemos a $\textcolor{red}{n}$, significa que la operación se acaba cuando $\textcolor{yellow}{i}$ tiene el valor de $\textcolor{red}{n}$.
		- a $\textcolor{red}{n}$ se le llama **límite superior**, y debe ser un número natural.
- esta operación se lee como “sumatoria de $a_{i}$ con $i$ variando de $1$ a $n$”.

ahora un ejemplo más concreto. podemos elevar $i$ al cuadrado y sumar los resultados hasta llegar a $i=4$:
$$\sum_{i=1}^{4} i^{2}=1^{2}+2^{2}+3^{2}+4^{2}=30$$

pero no es necesario siempre usar $i$, y su valor inicial no tiene porqué ser 1. aquí sumamos $n\cdot (n+1)$, yendo de 3 a 5:
$$\sum_{n=3}^{5} n(n+1)=3\cdot 4+4\cdot 5+5\cdot 6=62$$

## propiedades
si queremos sumar $a_{k}$ y cada término de $a_{k}$ se multiplica por un número constante $c$, podemos decir que:
$$\sum_{k=m}^{n} ca_{k}=c\cdot \sum_{k=m}^{n} a_{k}$$

si queremos sumar dos términos $a_{k}$ y $b_{k}$, podemos separarlos en dos sumatorios y luego sumar los resultados:
$$\sum_{k=m}^{n} (a_{k}+b_{k})=\sum_{k=m}^{n} a_{k}+\sum_{k=m}^{n} b_{k}$$
- también funciona para la resta.

### sumando $i$, $i^2$ y $i^{3}$
una fórmula equivalente a sumar $i$ es la siguiente:
$$\sum_{i=1}^{n} i=\frac{n(n+1)}{2}$$

también existe una fórmula para sumar $i^{2}$:
$$\sum_{i=1}^{n} i^{2}=\frac{n(n+1)(2n+1)}{6}$$

…y una para $i^3$:
$$\sum_{i=1}^{n} i^{3}=\left(\sum_{i=1}^{n} i\right)^{2}=\left(\frac{n(n+1)}{2}\right)^{2}=\frac{n^{2}(n+1)^{2}}{4}$$

### otros atajos
- sumar $1$ es igual a $n$: $\sum_{i=1}^{n} 1=n$
	- tiene sentido ya que, aunque $i$ no está en la suma, se sigue sumando tantas veces como haya valores desde $1$ a $n$. por lo tanto se estaría sumando $1$ una cantidad $n$ de veces.
- sumar un número constante $c$ es igual a $c\cdot n$: $\sum_{i=1}^{n} c=cn$
- sumar números impares es igual a $n^{2}$: $\sum_{i=1}^{n} (2i-1)=n^{2}$

## relacionado
- un concepto muy similar es la [[notación productoria]].
- el [[principio de inducción completa]] frecuentemente se aplica en una sumatoria, aunque no siempre es el caso.
- dentro de programación y algoritmos, un [[bucle]] puede imitar la acción de una sumatoria.

## por qué sumatoria?
la sumatoria es útil para acortar cálculos repetitivos que de otra forma serían largos de escribir. es frecuentemente usada en el ámbito de la estadística e informática.




