---
Created: 2024-05-20
---
# permutación con repetición

>[!abstract] definición
>teniendo $\alpha$ elementos de una clase, $\beta$ de otra clase, …, $\gamma$ de otra clase, siendo $\alpha+\beta+\dots+\gamma=m$, los grupos que se pueden formar tal que:
>- cada grupo está formado por los $m$ elementos dados.
>- ya que todos tienen los mismos elementos, dos grupos son diferentes si y sólo si difieren en el orden de los mismos.

concepto dentro del [[análisis combinatorio]].

tenemos un conjunto de $m$ elementos tal que $m=n$, pero dentro de nuestro conjunto, existen elementos que son indistinguibles entre sí. cómo podemos saber cuántas combinaciones posibles se pueden hacer?

para eso usamos la permutación con repetición. podemos decir que:
$$\large P_{\alpha,\beta,\dots,\gamma}^{m}=\frac{m!}{\alpha!\:\beta!\dots \gamma!}$$

## ejemplo 
digamos que tenemos las letras $BANANA$. cuántas combinaciones podemos hacer con estas letras?
- como podemos notar, hay letras repetidas: 3 $A$s y 2 $N$s.
- por lo tanto, para conocer la respuesta calculamos $P_{3,2,1}^{6}=\frac{6!}{3!\:2!\:1!}=\frac{720}{12}=60$.