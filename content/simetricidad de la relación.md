---
Created: 2024-03-30
aliases:
  - relación simétrica
  - simétrica
  - relación asimétrica
  - asimétrica
  - relación antisimétrica
  - antisimétrica
  - simetría
---
# simetría de una relación
#lógica 

>[!abstract] definición
>una de las [[propiedades de relaciones definidas en un conjunto]].

simbólicamente, $\forall a,\forall b\in A\colon(a,b)\in R\Rightarrow(b,a)\in R$. 

## simétrica
$R$ es **simétrica** en $A$ si para cada par $(a,b)$ en $R$, tambíen existe un par $(b,a)$. ^sim

digamos que hay un conjunto $A=\{ 1,2,3 \}$ y $R\subset A^{2}$:
- $R=\{(1,1),(2,3),(2,2),(3,2)\}$ es simétrica porque tenemos $(2,3)$ y $(3,2)$. nótese que como $(1,1)$ y $(2,2)$ son pares reflexivos, nos basta con un solo par presente.
- $R=\{ (1,2),(2,1),(1,3) \}$ *no* es simétrica porque no tenemos un par $(3,1)$ para $(1,3)$.

## asimétrica
$R$ es **asimétrica** en $A$ si y solo si $\forall a,\forall b\in A\colon(a,b)\in R\Rightarrow(b,a)\not\in R$. ningún par $(a,b)$ tiene un par $(b,a)$. ^asim

## antisimétrica
$R$ es **antisimétrica** en $A$ si y solo si $\forall a,\forall b\in A\colon(a,b)\in R\wedge(b,a)\in R\Rightarrow a=b$. una relación es antisimétrica cuando *los únicos pares simétricos son pares reflexivos* $(a,a)$, aunque no significa que deban estar presentes. ^antisim
- alternativamente, $a\neq b \wedge (a,b)\in R\Rightarrow (b,a)\notin R$.

esto significa que, por ejemplo, la relación $R=\{ (2,2),(1,2),(1,3) \}$ *si* es antisimétrica, aunque haya un par $(2,2)$ que también es simétrico.

debido a su definición, hay casos donde $R$ puede ser simétrica y antisimétrica a la vez, o asimétrica y antisimétrica.
- por ejemplo, cuando todos los pares de $R$ son pares $(a,a)$, hablamos de una relación *simétrica y antisimétrica*.

## por qué simetricidad de una relación?
esta propiedad asegura que si $a$ está relacionado con $b$, entonces $b$ está relacionado con $a$.