---
Created: 2024-03-30
aliases:
  - relación reflexiva
  - relación no reflexiva
  - relación arreflexiva
  - reflexión
  - reflexiva
  - no reflexiva
  - arreflexiva
---
# reflexividad de una relación
#lógica 

>[!abstract] definición
>una de las [[propiedades de relaciones definidas en un conjunto]].

simbólicamente, $\forall a\in A:(a,a)\in R$.

## reflexiva
$R$ es **reflexiva** en $A$ si para cada elemento $a$ en el conjunto $A$, existe un [[par ordenado]] de $a$ y si mismo ($(a,a)$) en $R$. es importante saber que *no todos los pares ordenados en $R$ deben ser de este tipo*. ^reflx

digamos que hay un conjunto $A=\{ 1,2,3 \}$ y $R\subset A^{2}$:
- $R=\{(1,2),(1,1),(2,2),(3,3)\}$ es reflexiva porque tenemos $(1,1)$, $(2,2)$ y $(3,3)$.
- $R=\{ (1,1),(2,3),(3,3) \}$ *no* es reflexiva porque no tenemos un par $(a,a)$ para $2$.
	- tambíen se puede expresar como $2\in A\wedge (2,2)\notin R$.

## no reflexiva
$R$ **no es reflexiva** en $A$ si y solo si $\exists a\in A/(a,a)\notin R$. basta con mostrar que *al menos un elemento* de $A$ no tiene su par $(a,a)$. ^no-reflx

## arreflexiva
$R$ es **arreflexiva** en $A$ si y solo si $A\Leftrightarrow\forall a\in A:(a,a)\notin R$. para decir que $R$ es arreflexiva debemos verificar que *ningún elemento* de $A$ tiene su par $(a,a)$ en la relación. ^arreflx

## por qué reflexividad de una relación?
esta propiedad asegura que cada elemento está relacionado con sí mismo.