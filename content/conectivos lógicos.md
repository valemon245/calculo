---
Created: 2024-03-10
aliases:
  - "conector lógico"
  - "conectores lógicos"
  - "operaciones proposicionales"
  - "operaciones lógicas"
---
# conectivos lógicos u operaciones lógicas

>[!abstract] definición
>símbolos que conectan dos [[proposición lógica|proposiciones]] en una sola más compleja, cuyo valor de verdad dependerá de los valores de las proposiciones que la forman.

utilizamos los conectivos lógicos para operar con proposiciones, cada símbolo representa una operación diferente:

| símbolo               | operación                    | significado en lenguaje natural          | tabla de verdad                                                                                                                                                                                                            |
| --------------------- | ---------------------------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $\sim$ <br>$\neg$     | [[negación lógica]]          | no $p$ <br>$p$ no es cierto              | $\begin{array}{\|c\|c\|}\hline p&\sim p\\\hline\text{V}&\text{F}\\\text{F}&\text{V}\\\hline\end{array}$                                                                                                                    |
| $\wedge$              | [[conjunción lógica]]        | $p$ y $q$                                | $\begin{array}{\|c\|c\|c\|}\hline p&q&p\wedge q\\\hline\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}\\\text{F}&\text{V}&\text{F}\\\text{F}&\text{F}&\text{F}\\\hline\end{array}$                                  |
| $\vee$                | [[disyunción inclusiva]]     | $p$ o $q$                                | $\begin{array}{\|c\|c\|c\|}\hline p&q&p\lor q\\\hline\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{V}\\\text{F}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{F}\\\hline\end{array}$                                    |
| $\veebar$<br>$\Delta$ | [[disyunción exclusiva]]<br> | $p$ o $q$ pero no ambos                  | $\begin{array}{\|c\|c\|c\|}\hline p&q&p\veebar q\\\hline\text{V}&\text{V}&\text{F}\\\text{V}&\text{F}&\text{V}\\\text{F}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{F}\\\hline\end{array}$                                 |
| $\Rightarrow$         | [[implicación lógica]]       | $p$ implica $q$ <br>si $p$, entonces $q$ | $\begin{array}{\|c\|c\|c\|}\hline p&q&p\Rightarrow q\\\hline\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}\\\text{F}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{V}\\\hline\end{array}$                             |
| $\Leftrightarrow$     | [[doble implicación]]        | $p$ si y sólo si $q$                     | $\begin{array}{\|c\|c\|c\|}\hline p&q&p\Leftrightarrow q\\\hline\mathrm{V}&\mathrm{V}&\mathrm{V}\\\mathrm{V}&\mathrm{F}&\mathrm{F}\\\mathrm{F}&\mathrm{V}&\mathrm{F}\\\mathrm{F}&\mathrm{F}&\mathrm{V}\\\hline\end{array}$ |

para representar todos los posibles valores de verdad de la proposición compuesta que resulte de operar entre proposiciones más simples, utilizamos [[tablas de verdad]].

## por qué conectivos lógicos?
son la forma que tenemos de relacionar proposiciones y operar con ellas dentro de la [[lógica proposicional MOC|lógica proposicional]]. también son importantes para entender [[simbología matemática]].