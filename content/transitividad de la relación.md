---
Created: 2024-03-30
aliases:
  - relación transitiva
  - relación no transitiva
  - relación atransitiva
  - transitiva
  - no transitiva
  - atransitiva
---
# transitividad de una relación
#lógica 

>[!abstract] definición
>una de las [[propiedades de relaciones definidas en un conjunto]].

simbólicamente, $\forall a,\forall b,\forall c\in A:(a,b)\in R\land(b,c)\in R\Rightarrow(a,c)\in R$.

## transitiva
$R$ es **transitiva** en $A$ si, cuando tenemos un par $(a,b)$ y un par $(b,c)$ en $R$, tambíen existe un par $(a,c)$ en $R$. ^trans

tenemos como ejemplo el conjunto $A=\{ 1,2,3,4 \}$ y $R\subset A^{2}$:
- $R=\{(1,1),(2,1),(1,2),(2,2),(2,3),(3,2)\}$
	- comenzamos a verificar tomando a $(1,1)$. lo vamos a comparar con otro par que, en este caso, comience con $1$.
		- encontramos que $(1,2)$ comienza con $1$, por lo que ahora necesitamos verificar que existe un conjunto con los elementos de los extremos, es decir $(1,2)$. como podemos ver, si existe.
	- seguimos con $(2,1)$. lo vamos a comparar con pares que comiencen con $1$.
		- $(1,1)$ comienza con $1$, y sí existe un conjunto $(2,1)$.
		- $(1,2)$ comienza con $1$, y sí existe un conjunto $(2,2)$.
	- seguimos con $(1,2)$. lo vamos a comparar con pares que comiencen con $2$.
		- $(2,1)$ comienza con $2$, y sí existe un conjunto $(1,1)$.
		- $(2,2)$ comienza con $2$, y sí existe un conjunto $(1,2)$.
		- $(2,3)$ comienza con $2$, sin embargo vemos que no existe $(1,3)$ en $R$. por lo tanto, *no* es transitiva en $A$.

cuando no podemos hallar un par $(a,b)$ que comparar con un par $(b,a)$, la relación sigue siendo transitiva ya que no hay forma de contradecir la propiedad.
- por ejemplo, $R=\{ (1,2),(3,4) \}$ es transitiva.

## no transitiva
$R$ **no es transitiva** en $A$ si y solo si $\exists a,\exists b,\exists c\in A/(a,b)\in R,(b,c)\in R\land(a,c)\notin R$. basta con mostrar que existe *al menos un caso* donde hay un par $(a,b)$ y $(b,c)$ en $R$, pero no un $(a,c)$. ^no-trans

## atransitiva
$R$ es **atransitiva** en $A$ si y solo si $\forall a,\forall b,\forall c\in A:(a,b)\in R\land(b,c)\in R\Rightarrow(a,c)\not\in R$. ^atrans

## por qué transitividad de la relación?
esta propiedad asegura que si $a$ está relacionado con $b$, y $b$ está relacionada con $c$, entonces $a$ está relacionado con $c$.