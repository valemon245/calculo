---
Created: 2024-04-04
aliases:
  - ley lógica
---
# tautología o ley lógica

>[!abstract] definición
>una [[proposición lógica|proposición]] que siempre es verdadera.

las tautologías son proposiciones que siempre son verdaderas, sin importar el valor de sus proposiciones más atómicas. 

un ejemplo es $[(p\Rightarrow q)\wedge p]\Rightarrow q$, donde podemos ver que su [[tablas de verdad|tabla]] solo tiene $V$s:
$$\begin{array}{|c|c|c|c|c|}\hline p&q&p\Rightarrow q&(p\Rightarrow q)\wedge p&[(p\Rightarrow q)\wedge p]\Rightarrow q\\\hline\text{V}&\text{V}&\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}&\text{F}&\text{V}\\\text{F}&\text{V}&\text{V}&\text{F}&\text{V}\\\text{F}&\text{F}&\text{V}&\text{F}&\text{V}\\\hline\end{array}$$