---
Created: 2024-05-20
---

>[!abstract] definición
>todos los grupos diferentes que se pueden formar tal que:
>- cada grupo está formado por $n$ elementos de $m$ dados, *no necesariamente distintos*.
>- dos grupos son distintos si y sólo si difieren en algún elemento o en el orden de los mismos.

concepto del [[análisis combinatorio]]. se lee “arreglos de los $m$ elementos distintos que se pueden repetir hasta $n$ veces”.

a diferencia del [[arreglo simple]], los elementos se pueden repetir. podemos decir que:
$$A_{n,r}^{m}=\underbrace{m\cdot m\cdot m\cdot\dots\cdot m}_{n \text{ veces}}=m^{n}$$

un ejemplo: queremos conocer cuántos números de 3 cifras se pueden crear con $0,1,2,3,4,5,6$. 
- como podemos notar, el primer lugar del número no puede ser 0, ya que nos quedaría un número de 2 cifras. nuestro primer lugar solo tiene 5 posibilidades.
- por lo tanto, la respuesta es $5\cdot A_{2,r}^{6}=5\cdot 6^{2}=5\cdot 36=180$.