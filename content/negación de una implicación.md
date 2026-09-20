---
Created: 2024-03-30
---
# negación de una implicación

>[!abstract] definición
>una posible forma de [[negación lógica|negar]] una [[implicación lógica]].

$p\Rightarrow q$ y $\neg(p\land \neg q)$ son equivalentes:
$$ \begin{array}{|c|c|c|c|c|}\hline p&q&p\Rightarrow q&-(p\land-q)&(p\Rightarrow q)\Leftrightarrow-(p\land-q)\\\hline\text{V}&\text{V}&\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}&\text{F}&\text{V}\\\text{F}&\text{V}&\text{V}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{V}&\text{V}&\text{V}\\\hline\end{array}$$

por lo tanto, la negación de la primera equivale a la negación de la segunda: $$ \neg \left(p\Rightarrow q\right)\Leftrightarrow\neg \left[\neg \left(p\wedge-q\right)\right] \;\;\; = \;\;\; \neg (p\Rightarrow q)\Leftrightarrow (p\wedge\neg q)$$
podemos decir, entonces, que la negación de un condicional es la conjunción del antecedente y la negación del consecuente.

por ejemplo:
- “si hoy es lunes, entonces mañana es miércoles” ($F$) pasa a ser “hoy es lunes y mañana *no* es miércoles” ($V$)
- $1=-1\Rightarrow1^2=\left(-1\right)^2$ ($V$) pasa a ser $1=-1\wedge1^2\neq\left(-1\right)^2$ ($F$)

ver [[proposiciones equivalentes|propiedades de las proposiciones]] para otras propiedades.