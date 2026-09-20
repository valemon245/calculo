---
Created: 2024-04-27
---
# inducción: ejercicios
#matematica 

>[!emoji] 📌 
>[[principio de inducción completa]]

## observaciones generales
para demostrar que $P(h+1)$ (tesis inductiva) es verdadera, tenemos que utilizar la hipótesis inductiva de alguna forma.
- en los casos donde tenemos una igualdad en la proposición, esto suele significar ==buscar alguna forma en la cual uno de los lados de la igualdad en nuestra H.I. aparezca en la tesis.==

las propiedades más útiles son:
- **distributiva**: $a(b+c)=a\cdot b + a\cdot c$
- **factor común**: $a\cdot b + a\cdot c=a(b+c)$
- **elemento neutro**: multiplicar un término por 1.
	- su uso en la inducción es multiplicar un término $a$ por una fracción equivalente a 1, por ejemplo $a\cdot \frac{5}{5}=\frac{5a}{5}$.
		- también podemos decir que se multiplica y divide un término por $5$, en este caso.
- **suma de fracciones con mismo denominador**: $\frac{a}{b}+\frac{c}{b} = \frac{a+c}{b}$
	- el elemento neutro se aplica en un término $a$ con el objetivo de luego sumarlo a otro término $c$ que ahora tiene el mismo denominador.
- **asociativa**: $a+(b+c) = (a+b)+c$
- **conmutativa**: $a+b=b+a$
- **cuadrado de un binomio**: $(a+b)^{2}=a^{2}+2ab+b^{2}$
	- se suele usar en $(h+1)^{2}$.
		- a veces también se puede usar en $h^{2}+2h+1$, en orden inverso.
- **producto de potencia de misma base**: $a^{n}\cdot a^{m}=a^{n+m}$
	- está propiedad se suele usar a la inversa en la inducción. por ejemplo, $3^{h+1} = 3^{h}\cdot 3^{1} = 3^{h}\cdot 3$.

## ejemplos

demostrar por inducción que $\forall n\in\mathbb{N},\sum_{i=1}^{n} i=\frac{n(n+1)}{2}$
>[!toggle|pink]- solución
>**paso 1:** demostrar que $P(1)$ es verdadera.
>$$\text{si } n=1, \text{ entonces } \sum_{i=1}^{1} i=1=\frac{1(1+1)}{2}=\frac{1\cdot 2}{2}=\frac{2}{2}=1$$
>
>**paso 2:** suponer que $P(h)$ es verdadera (hipótesis inductiva)
>$$\text{si } n=h, \text{ entonces } \sum_{i=1}^{h} i=\frac{h(h+1)}{2}$$
>
>**paso 3:** demostrar que $P(h+1)$ es verdadera.
>$$\text{si } n=h+1, \text{ entonces } \sum_{i=1}^{h+1} i=\frac{(h+1)[(h+1)+1]}{2}$$
>
>ahora debemos demostrar que la tesis inductiva es verdadera.
>
>cuando tenemos una [[notación sumatoria|sumatoria]], una forma rápida de lograr esto es descomponiéndola en la sumatoria de $P(h)$ y sumando al último término con índice $h+1$ por separado. 
>$$\sum_{i=1}^{h+1}i=\sum_{i=1}^{h}i+(h+1)$$
>
>ahora que un lado de la igualdad en $P(h)$ está presente, podemos reemplazarlo por el otro lado. entonces, tenemos:
>$$\sum_{i=1}^{h}i+(h+1)=\frac{h(h+1)}{2} + (h+1)$$
>
>podemos comenzar a resolver; el objetivo es llegar al otro lado de la igualdad en $P(h+1)$.

