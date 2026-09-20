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

|símbolo|operación|significado en lenguaje natural|tabla de verdad|
|---|---|---|---|
|$\sim$ $\neg$|[[negación lógica]]|no $p$ $p$ no es cierto|$\begin{matrix} p & \sim p \ \hline \mathrm{V} & \mathrm{F} \ \mathrm{F} & \mathrm{V} \end{matrix}$|
|$\wedge$|[[conjunción lógica]]|$p$ y $q$|$\begin{matrix} p & q & p\wedge q \ \hline \mathrm{V} & \mathrm{V} & \mathrm{V} \ \mathrm{V} & \mathrm{F} & \mathrm{F} \ \mathrm{F} & \mathrm{V} & \mathrm{F} \ \mathrm{F} & \mathrm{F} & \mathrm{F} \end{matrix}$|
|$\vee$|[[disyunción inclusiva]]|$p$ o $q$|$\begin{matrix} p & q & p\lor q \ \hline \mathrm{V} & \mathrm{V} & \mathrm{V} \ \mathrm{V} & \mathrm{F} & \mathrm{V} \ \mathrm{F} & \mathrm{V} & \mathrm{V} \ \mathrm{F} & \mathrm{F} & \mathrm{F} \end{matrix}$|
|$\veebar$ $\Delta$|[[disyunción exclusiva]]|$p$ o $q$ pero no ambos|$\begin{matrix} p & q & p\veebar q \ \hline \mathrm{V} & \mathrm{V} & \mathrm{F} \ \mathrm{V} & \mathrm{F} & \mathrm{V} \ \mathrm{F} & \mathrm{V} & \mathrm{V} \ \mathrm{F} & \mathrm{F} & \mathrm{F} \end{matrix}$|
|$\Rightarrow$|[[implicación lógica]]|$p$ implica $q$ si $p$, entonces $q$|$\begin{matrix} p & q & p\Rightarrow q \ \hline \mathrm{V} & \mathrm{V} & \mathrm{V} \ \mathrm{V} & \mathrm{F} & \mathrm{F} \ \mathrm{F} & \mathrm{V} & \mathrm{V} \ \mathrm{F} & \mathrm{F} & \mathrm{V} \end{matrix}$|
|$\Leftrightarrow$|[[doble implicación]]|$p$ si y sólo si $q$|$\begin{matrix} p & q & p\Leftrightarrow q \ \hline \mathrm{V} & \mathrm{V} & \mathrm{V} \ \mathrm{V} & \mathrm{F} & \mathrm{F} \ \mathrm{F} & \mathrm{V} & \mathrm{F} \ \mathrm{F} & \mathrm{F} & \mathrm{V} \end{matrix}$|

para representar todos los posibles valores de verdad de la proposición compuesta que resulte de operar entre proposiciones más simples, utilizamos [[tablas de verdad]].

## por qué conectivos lógicos?
son la forma que tenemos de relacionar proposiciones y operar con ellas dentro de la [[lógica proposicional MOC|lógica proposicional]]. también son importantes para entender [[simbología matemática]].