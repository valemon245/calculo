---
Created: 2024-05-20
aliases:
  - triángulo de tartaglia
---
# triángulo de pascal o de tartaglia

>[!abstract] definición
>disposición ordenada de todos los [[número combinatorio|números combinatorios]] en forma de triángulo.

![[alg_triangulodepascal.png]]

podemos ver que:
- en el primer renglón están todos los números combinatorios de numerador 0; en el segundo renglón están todos los números combinatorios de numerador 1; en el tercer renglón los de numerador 2, y así.
- en cada renglón los denominadores crecen desde 0 hasta el numerador correspondiente a ese renglón.
- todos los nros. combinatorios de los laterales dan 1, porque sus denominadores son 0 o iguales al numerador.
- cada nro. combinatorio es resultado de la suma de los dos nros. arriba de este (marcado en rojo). ver [[fórmula de stieffel]].

el tríangulo de pascal es útil para hallar los números combinatorios usados en el [[binomio de newton]].