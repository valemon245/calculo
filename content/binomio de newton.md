---
Created: 2024-05-20
---
# potencias del binomio

>[!abstract] definición
>fórmula para calcular las potencias de un binomio, siendo el exponente un entero positivo.

veamos como se desarrollan las potencias del binomio $(a+b)$:
$$  
\begin{aligned}  
(a+b)^{1} &= a+b\  
(a+b)^{2} &= (a+b)\cdot(a+b)=a^{2}+2ab+b^{2}\  
(a+b)^{3} &= (a+b)^{2}\cdot(a+b)=(a^{2}+2ab+b^{2})\cdot(a+b)=a^{3}+3a^{2}b+3ab^{2}+b^{3}\  
(a+b)^{4} &= (a+b)^{3}\cdot(a+b)=(a^{3}+3a^{2}b+3ab^{2}+b^{3})\cdot(a+b)=a^{4}+4a^{3}b+6a^{2}b^{2}+4ab^{3}+b^{4}\  
&\vdots\  
(a+b)^{n} &= ;?  
\end{aligned}  
$$

usando [[número combinatorio|números combinatorios]], podemos definir una fórmula para conocer la potencia de $(a+b)^n$:
$$(a+b)^n={n \choose 0}a^nb^0+{n \choose 1}a^{n-1}b^1+{n \choose 2}a^{n-2}b^2+\dots+{n \choose n-1}a^{n-(n-1)}b^{n-1}+{n \choose n}a^{n-n}b^n$$

podemos mirar la línea con numerador $n$ en el [[triángulo de pascal]] para hallar los valores del nro. combinatorio en cada término.

abreviándolo usando la [[notación sumatoria|sumatoria]], podemos decir que:
$$(a+b)^n=\sum_{i=0}^n\binom{n}{i}a^{n-i}b^i$$

existe una fórmula para hallar el [[término k-ésimo]] o central.

## propiedades 
- contiene $n+1$ términos no semejantes (porque se empieza por $k=0$).
- cada término es el producto de:
	- un número combinatorio,
	- una potencia de $a$,
	- y una potencia de $b$.
- los nros. combinatorios involucrados son todos de numerador $n$, y sus denominadores van de 0 a $n$.
- en cada término, el exponente de $a$ va de $n$ a 0 y el exponente de $b$ va de 0 a $n$.
- la suma de los exponentes de $a$ y $b$ en cada término es igual a $n$.
- los nros. combinatorios equidistantes de los extremos son complementarios.

