---
Created: 2024-05-20
aliases:
  - números combinatorios
  - coeficiente binomial
---
# número combinatorio

>[!abstract] definición
>teniendo dos enteros no negativos $m$ y $n$ donde $n\leqslant m$, notación que representa el número de formas en que se pueden conseguir grupos de $n$ componentes a partir de un [[conjunto]] de $m$ elementos, sin importar su orden.

concepto dentro del [[análisis combinatorio]], también se le llama **coeficiente binomial**. es una notación diferente a la [[combinación simple]] $C_n^m$, pero se refieren a lo mismo. 
$${\textcolor{red}{\underset{\text{\large numerador}}{m}}\choose \textcolor{blue}{\underset{\text{\large denominador/orden}}{n}}}=\frac{m!}{n!(m-n)!}$$

## propiedades
todo número combinatorio de denominador 0 es igual a 1:
$${m\choose 0}=\frac{m!}{0!\:m!}=1$$

todo número combinatorio de denominador 1 es igual al numerador:
$${m \choose 1}=\frac{m!}{1!(m-1)!}=\frac{m\cdot(m-1)!}{(m-1)!}=m$$

todo número combinatorio donde el numerador es igual al denominador es igual al 1:
$${m\choose m}=\frac{m!}{m!(m-m)!}=1$$

## relacionado
- existen casos especiales donde podemos decir que dos nros. combinatorios son [[números combinatorios complementarios|complementarios]].
- también hay casos donde la suma de dos nros. combinatorios nos da otro nro. combinatorio: [[fórmula de stieffel]].
- usando las propiedades y la fórmula antes mencionada, podemos crear el [[triángulo de pascal]].
- los nros. combinatorios se usan en el [[binomio de newton]].

