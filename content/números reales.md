---
Created: 2023-09-09
aliases:
  - ℝ
  - reales
  - número real
  - real
  - axiomas de los reales
  - axioma del supremo
---
# números reales
#matematica 

>[!abstract] definición
>[[conjuntos numéricos|conjunto numérico]] que incluye a los [[números racionales]] e [[números irracionales|irracionales]].

representado por el carácter especial $\mathbb{R}$. simbólicamente, podemos decir que $\mathbb{R}=\mathbb{Q}\cup \mathbb{I}$.

está incluído dentro de los [[números complejos]].

$\mathbb{R}$ no es sólamente un conjunto de elementos, es una estructura algebráica (cuerpo) que cumple ciertos axiomas.

## definición de $\mathbb{R}$
formalmente, representamos el sistema de números reales como $(\mathbb{R}, +,\cdot,<)$:
- el conjunto formado por los elementos de $\mathbb{R}$, que llamamos números reales.
- la operación de suma en $\mathbb{R}$, con sus reglas y propiedades.
- la operación de producto en $\mathbb{R}$, con sus reglas y propiedades.
- la relación de orden en $\mathbb{R}$, llamada desigualdad.

hay varias formas de definir a $\mathbb{R}$. axiomáticamente, podemos decir que:
- el conjunto $\mathbb{R}$ es un *cuerpo*: las operaciones básicas de suma y producto están definidas y tienen las propiedades usuales.
- $\mathbb{R}$ es un cuerpo *totalmente ordenado*: cumple con los axiomas del orden, y el orden es compatible con las operaciones del cuerpo.
- $\mathbb{R}$ es *completo*: satisface el axioma del supremo.
	- este último axioma marca la diferencia entre $\mathbb{R}$ y $\mathbb{Q}$, que no es un sistema completo.

## propiedades
se verifican las siguientes propiedades o axiomas en $\mathbb{R}$:

### respecto a la suma (axiomas algebráicos)
- ley de cierre: $\forall a,b\in\mathbb{R}:a+b\in\mathbb{R}$
- propiedad conmutativa: $\forall a,b\in\mathbb{R}:a+b=b+a$
- propiedad asociativa: $\forall a,b,c\in\mathbb{R}:(a+b)+c=a+(b+c)$
- existencia de elemento neutro: $\exists 0 \in \mathbb{R}/\forall a\in\mathbb{R}:a+0=0+a=a$
- existencia de opuesto: $\forall a\in\mathbb{R},\exists(-a)\in\mathbb{R}/-a+a=a+(-a)=0$

### respecto al producto (axiomas algebráicos)
- ley de cierre: $\forall a,b\in\mathbb{R}:a\cdot b\in\mathbb{R}$
- propiedad conmutativa: $\forall a,b\in\mathbb{R}:a\cdot b=b\cdot a$
- propiedad asociativa: $\forall a,b,c\in\mathbb{R}:(a\cdot b)\cdot c=a\cdot (b\cdot c)$
- existencia de elemento neutro: $\exists 1 \in \mathbb{R}/\forall a\in\mathbb{R}:a\cdot 1=1\cdot a= a$
- existencia de inverso para elementos no nulos: $\forall a\in\mathbb{R},a\neq 0:\exists a^{-1} \in \mathbb{R}/a\cdot a^{-1}=1$
- distributiva con respecto a la suma: $\forall a,b,c\in\mathbb{R}:(a+b)\cdot c=a\cdot c + b\cdot c$

### axiomas de orden
- ley de tricotomía: teniendo $a,b\in\mathbb{R}$, solo uno de los siguientes casos se verifica: $a=b,\;a<b,\;b<a$
- propiedad transitiva: $\forall a,b,c\in\mathbb{R}:a<b\wedge b<c \Rightarrow a<c$
- consistencia respecto a la suma: $\forall a,b,c\in\mathbb{R}:a<b\Rightarrow a+c<b+c$
- consistencia restringida respecto al producto: $\forall a,b,c\in\mathbb{R}:a<b\wedge c\neq 0\Rightarrow a\cdot c<b\cdot c$

### axioma del supremo
el axioma del supremo dice que “todo subconjunto real no vacío y [[conjunto acotado|acotado superiormente]], admite supremo en $\mathbb{R}$”.

el **supremo** de $S$ sería el menor de todas las cotas superiores posibles, representado como $sup(S)$.

este axioma o propiedad asegura que no hay “huecos” en $\mathbb{R}$. también implica el **principio de arquímedes**.

### otras propiedades
además de los axiomas anteriores, $\mathbb{R}$ también cumple:
- entre dos números reales hay otro número real: $a,b\in \mathbb{R}/a<b\Rightarrow\exists c\in \mathbb{R}/a<c<b$.
- principio de arquímedes: dado un número real, siempre se puede hallar un natural mayor a este. en otras palabras, $\mathbb{R}$ no está acotado superiormente.
	- simbólicamente, $\forall a\in \mathbb{R},\exists n\in N/n\geq a$.