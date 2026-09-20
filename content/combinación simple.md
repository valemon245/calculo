---
Created: 2024-05-20
---

>[!abstract] definición
>siendo $n\leqslant m$, todos los grupos distintos que se pueden formar tal que:
>- cada grupo está formado por $n$ elementos de los $m$ dados.
>- dos grupos son distintos si y sólo si difieren en sus elementos.

concepto dentro del [[análisis combinatorio]]. se lee “combinaciones simples de los $m$ elementos de un conjunto tomados de a $n$”.
$$C_n^m=\frac{m!}{n!(m-n)!}$$

a diferencia del [[arreglo simple]], *no importa el orden de los elementos*. una notación alternativa a la combinación es el [[número combinatorio]].

## ejemplo
digamos que tenemos 5 alumnos diferentes, de los cuales 3 se deben elegir para recibir el mismo premio cada uno. cuántas formas diferentes se pueden elegir?

![[alg_arreglo.png]]

usar un arreglo en este caso es ineficiente ya que el orden de los elementos no nos interesa, los 3 alumnos reciben lo mismo. el resultado entonces, sería el número de columnas en la imagen.

la cantidad total de grupos posibles es $A_{3}^{5}=60$. en cada columna hay 6 elementos, lo que es igual a $P_{3}=6$. entonces:
$$\frac{60}{6}=10 \text{ columnas}$$

por lo tanto, podemos decir que:
$$\frac{\text{nro. total de grupos}}{\text{nro. de grupos por columna}}=\frac{A_{n}^{m}}{P_{n}}=\frac{\frac{m!}{(m-n)!}}{n!}=\frac{m!}{n!(m-n)!}=C_{n}^{m}$$

***

en la calculadora, podemos calcular una combinación usando la tecla `nCr`:
![[alg_calculadora-ncr.png|350]]
