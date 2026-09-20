---
Created: 2024-03-10
---
# condiciones suficientes y/o necesarias

>[!abstract] definición
>una condición es suficiente cuando su presencia (veracidad) garantiza que un evento o afirmación también pase, pero su ausencia no impide que dicho evento ocurra.
>
>una condición es necesaria cuando su ausencia (falsedad) impide que pase un evento o afirmación, pero su presencia no nos garantiza que dicho evento vaya a ocurrir.

## en el [[implicación lógica|condicional]]
>[!caution] si la implicación es falsa, no se puede hablar de condiciones necesarias y suficientes.

cuando $p\Rightarrow q$ es verdadero, podemos decir que:
- $p$ es **condición suficiente** para $q$.
- $q$ es **condición necesaria** para $p$.

pero qué significa esto exactamente? veámoslo con un ejemplo: “si soy un perro, entonces soy un animal”.
- $p$: soy un perro.
- $q$: soy un animal.

ser un perro es suficiente para afirmar que uno es un animal también, sin embargo no es algo necesario para ser un animal; podría haber sido de otra especie como un gato o un ave, y aún así sería un animal.

decimos que $p$ es una condición suficiente porque *su presencia garantiza que $q$ ocurra, pero su ausencia no nos dice que $q$ no vaya a ocurrir*; la proposición $q$ puede ser verdadera por otras condiciones.

por otro lado, si uno *no* es un animal, entonces no puede ser un perro. sin embargo, ser un animal no nos garantiza que vayamos a ser un perro también.

decimos que $q$ es una condición necesaria porque *su ausencia impide que $p$ ocurra, pero su presencia no nos garantiza la veracidad de $p$*.

esto se puede apreciar en la [[tablas de verdad|tabla]] de la implicación
$$\begin{array}{|c|c|c|}\hline p&q&p\Rightarrow q\\\hline\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}\\\text{F}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{V}\\\hline\end{array}$$
…donde notamos que:
- cuando $p$ está presente (es verdadera), $q$ también debe serlo para que el condicional sea verdadero; cuando $p$ es falsa, $q$ puede tener cualquier valor y el condicional seguirá siendo verdadero.
- cuando $q$ está ausente (es falsa), $p$ debe ser falsa también para que el condicional sea verdadero; cuando $q$ es verdadera, $p$ puede tener cualquier valor y el condicional seguirá siendo verdadero.

esto también nos dice que *$p$ es un [[relación de inclusión|subconjunto]] de $q$*.

## en el [[doble implicación|bicondicional]]
tenemos otro ejemplo: “$n$ es par si y sólo si $n$ es múltiplo de 2”
- $p$: $n$ es un número par natural.
- $q$: $n$ es múltiplo natural de 2.

si $n$ no es par, entonces no puede ser múltiplo natural de dos y viceversa. podemos decir entonces que tanto $p$ como $q$ son **suficientes y necesarias** una para la otra.

también significa que *$p$ y $q$ son el mismo conjunto*, confirmando que al bicondicional se lo puede ver como una [[proposiciones equivalentes|equivalencia]].

## por qué condiciones suficientes y/o necesarias?
es importante entender los conceptos de una condición suficiente y/o necesaria para el análisis de los condicionales.