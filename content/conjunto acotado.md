---
Created: 2024-06-20
aliases:
  - cota superior
  - cota inferior
  - acotado superiormente
  - acotado inferiormente
  - acotado
---
# conjunto acotado

>[!abstract] definición
>[[conjunto]] de [[números reales]] para el que existe un número real mayor/menor o igual que todos sus elementos.

es decir, $S\subseteq \mathbb{R}$ está **acotado superiormente** si y sólo si existe un $k$ real tal que $\forall x \in S:x\leq k$.
- a $k$ se le llama **cota superior**.

por otra parte, $S\subseteq \mathbb{R}$ está **acotado inferiormente** si y sólo si existe un $g$ real tal que $\forall x \in S:g\leq x$.
- a $g$ se le llama **cota inferior**.

las cotas no necesariamente tienen que ser partes de $S$. si un conjunto tiene cota superior e inferior, podemos decir que está contenido en un intervalo finito.

el [[números reales#axioma del supremo|axioma del supremo]] asegura que cualquier $S$ no vacío acotado superiormente en $\mathbb{R}$ tiene un supremo en $\mathbb{R}$.

## ejemplos
- $S=\{ 1,2,3 \}$: acotado superiormente por cualquier número mayor o igual a 3.
- $S=\{ x \in\mathbb{R} / x<1 \}$: acotado superiormente por cualquier número mayor o igual a 1. 
- $S=\{ x \in\mathbb{N} \}$: ya que el conjunto de naturales no tiene último elemento, no existe un $k$ real tal que $x\leq k$ y por lo tanto, no está acotado superiormente.