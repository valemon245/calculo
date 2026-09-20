---
Created: 2024-03-10
---
# tablas de verdad
#lógica 

>[!abstract] definición
>tabla donde se listan todos los valores de verdad posibles para una [[proposición lógica|proposición]] compuesta, basado en los valores de sus proposiciones atómicas.

por $n$ cantidad de proposiciones simples, tendremos $2^{n}$ cantidad de filas en la tabla.

## precedencia de operadores
similar al PEMDSR en matemáticas, se estableció un orden en el que resolver cada [[conectivos lógicos|conector lógico]] de una proposición compuesta. de primero a último, tenemos:
1. negación
2. conjunción
3. disyunción
4. condicional
5. bicondicional

por ejemplo, $\neg p\wedge q\Rightarrow r$ se resuelve como $\left[ \left( \neg p\right) \wedge q\right] \Rightarrow r$
$$ \begin{array}{|c|c|c|c|c|c|}\hline p&q&r&\neg p&\neg p \wedge q&\neg p \wedge q \Rightarrow r\\\hline \text{V}&\text{V}&\text{V}&\text{F}&\text{F}&\text{V}\\\text{V}&\text{V}&\text{F}&\text{F}&\text{F}&\text{V}\\\text{V}&\text{F}&\text{V}&\text{F}&\text{F}&\text{V}\\\text{V}&\text{F}&\text{F}&\text{F}&\text{F}&\text{V}\\\text{F}&\text{V}&\text{V}&\text{V}&\text{V}&\text{V}\\\text{F}&\text{V}&\text{F}&\text{V}&\text{V}&\text{F}\\\text{F}&\text{F}&\text{V}&\text{V}&\text{F}&\text{V}\\\text{F}&\text{F}&\text{F}&\text{V}&\text{F}&\text{V}\\\hline\end{array}$$

otros ejemplos:
$$ \begin{array}{c|c}\text{proposición sin paréntesis}&\text{proposición con paréntesis}\\\hline\lnot p\land q&(\lnot p)\land q\\p\lor\lnot q&p\lor(\lnot q)\\p\land q\lor r&(p\land q)\lor r\\p\lor q\land r&p\lor(q\land r)\\p\Rightarrow q\Leftrightarrow r&(p\Rightarrow q)\Leftrightarrow r\\p\lor q\Rightarrow r&(p\lor q)\Rightarrow r\end{array}$$

## clasificaciones
dependiendo de su tabla de verdad, podemos clasificar las proposiciones en [[tautología|tautologías]], [[contradicción|contradicciones]] o [[contingencia|contingencias]]. cuando dos proposiciones tienen la misma tabla de verdad, se las considera [[proposiciones equivalentes]].
