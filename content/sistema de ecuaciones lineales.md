---
Created: 2024-06-24
---
# sistema de ecuaciones lineales

>[!abstract] definición
>conjunto de [[ecuación lineal|ecuaciones lineales]] con más de una incógnita, con sus coeficientes definidos en un cuerpo.

definimos un sistema de $m$ ecuaciones lineales con $n$ incógnitas como:
$$\large \begin{cases}a_{11}x_1+a_{12}x_2+\dots+a_{1n}x_n=b_1\\a_{21}x_1+a_{22}x_2+\dots+a_{2n}x_n=b_2\\\dots\dots\dots\dots\\a_{m1}x_1+a_{m2}x_2+\dots+a_{mn}x_n=b_m\end{cases}$$
- $m$ es el número de ecuaciones,
- $n$ es el número de incógnitas,
- $a_{ij}\in\mathbb{R}$ es el coeficiente de la incógnita $x_j$ en la $i$-ésima ecuación,
	- en este caso, están definidos en el cuerpo de los [[números reales|reales]].
	- $i$ indica la ecuación del coeficiente,
	- $j$ indica la incógnita del coeficiente,
- $x_j$ son las incógnitas,
- $b_i$ son los términos independientes.

abreviando con la [[notación sumatoria|sumatoria]], podemos decir que:
$$\large\sum_{j=1}^na_{ij}\cdot x_j=b_i\quad;\quad i=1,2,\dots m$$

los sistemas de ecuaciones lineales conforman un problema matemático, siendo este el hallar los valores de las incógnitas que verifican simultáneamente todas las ecuaciones del sistema. 

## soluciones
una **solución del sistema** es una n-úpla $(\alpha_{1},\alpha_{2},\alpha_{3},\dots,\alpha_{n})\in\mathbb{R}^{n}$ tal que, al reemplazar cada incógnita por cada $\alpha$ de forma ordenada, satisface todas las ecuaciones simultáneamente. 

el **conjunto solución** $S$ o $Sol$ contiene a todas las n-úplas que son soluciones de un sistema. 

## clasificación
según la cantidad de incógnitas y ecuaciones de un sistema, podemos decir que es un:
- **sistema cuadrado**, si $m=n$.
- **sistema rectangular**, si $m\neq n$.

según el conjunto solución de un sistema, podemos clasificarlo en:
- **incompatible** o inconsistente: no tiene solución. 
	- en una gráfica, veríamos que las líneas de todas las ecuaciones nunca se cruzan.
	- en este caso, decimos que $S=\varnothing$. no existe ninguna n-úpla que verifique todas las ecuaciones a la vez.
- **compatible** o consistente: sí tiene solución.
	- **determinado**: tiene una única solución.
		- en una gráfica, veríamos que las lineas de las ecuaciones se cruzan en un solo punto específico.
	- **indeterminado**: tiene infinitas soluciones.
		- en una gráfica, veríamos que las líneas se las ecuaciones están superpuestas.
		- esto significa que al menos una ecuación no brindó ninguna información nueva al sistema. ver [[dependencia e independencia lineal]].

dos sistemas son **equivalentes** si y sólo sí comparten el mismo conjunto solución.

## relacionado
- [[expresión matricial de un sistema de ecuaciones]]
	- [[teorema fundamental de equivalencia]]
- [[teorema de rouché-frobenius]]
- [[sistema crameriano]]
- [[teorema de cramer]]
- [[regla de cramer]]
- [[sistema de ecuaciones homogéneo]]