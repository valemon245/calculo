---
Created: 2024-06-21
---
# unidad imaginaria

>[!abstract] definición
>concepto matemático para resolver ecuaciones que no tienen solución en el conjunto de los [[números reales]].

la unidad imaginaria $i$ está definida por una sola propiedad: su cuadrado es igual a -1. por definición, implica que $i$ y $-i$ son raíces cuadradas de -1.

$i$ se introduce para expandir los reales hacia un sistema de [[números complejos]]. en forma de par ordenado, decimos que $i=(0,1)$.

## potencias de $i$
sabiendo que $i^{2}=-1$, podemos decir que:
$$\large\begin{align}
& i^{0} = 1 \\
& i^{1} = i = \sqrt{ -1 }\\
& i^{2} = -1 \\
& i^{3} = i^{2}\cdot i = (-1)\cdot i = -i \\
& i^{4} = i^{2}\cdot i^{2} = (-1)\cdot (-1) = 1
\end{align}
$$

las potencias de $i$ siguen un patrón infinitamente: $1,i,-1,-i$.

## simplificación
sabiendo que las potencias de $i$ siguen un patrón de 4 posibles valores, podemos simplificar potencias de grandes exponentes. 

la mejor forma de hacer esto es ver a cualquier exponente de $i$ como su división por 4 (ver [[algoritmo de la división]]).

por ejemplo, tenemos $i^{42}$:
$$\large\begin{align}
i^{42} & = i^{4\cdot 10 + 2} \\
& = i^{4\cdot 10} \cdot i^{2} \\
& = (i^{4})^{10} \cdot i^{2} \\
& = 1^{10} \cdot i^{2} \\ 
& = 1 \cdot i^{2} \\
& = 1 \cdot (-1) \\
& = -1
\end{align}
$$

$i$ elevada a cualquier exponente va a ser igual a $i$ elevada al resto de dividir dicho exponente por 4.