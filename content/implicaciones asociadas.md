---
Created: 2024-03-30
---
# implicaciones asociadas

>[!abstract] definición
>posibles [[implicación lógica|implicaciones]] que se obtienen de una implicación original.

a partir de un condicional directo $p\Rightarrow q$, se pueden conseguir otros condicionales asociados:
- **recíproco**: $q\Rightarrow p$
- **contrario**: $\neg p\Rightarrow \neg q$
- **contrarrecíproco**: $\neg q\Rightarrow \neg p$

![[Captura de pantalla 2024-03-10 204833.png|500]]

los contrarrecíprocos son [[proposiciones equivalentes|equivalentes]] al condicional, es decir, tienen la misma tabla de verdad:
$$\begin{array}{|c|c|c|c|c|}\hline p&q&\neg p&\neg q&\neg q\Rightarrow \neg  p\\\hline\text{V}&\text{V}&\text{F}&\text{F}&\text{V}\\\text{V}&\text{F}&\text{F}&\text{V}&\text{F}\\\text{F}&\text{V}&\text{V}&\text{F}&\text{V}\\\text{F}&\text{F}&\text{V}&\text{V}&\text{V}\\\hline\end{array}$$
por lo tanto, $(p\Rightarrow q)\Leftrightarrow(\neg q\Rightarrow \neg p)$ es una [[tautología]].
