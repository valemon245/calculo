---
Created: 2023-11-12
aliases:
  - Ecuaciones de segundo grado
---
# ecuaciones de segundo grado

las ecuaciones de segundo grado son aquellas donde haya una potencia al cuadrado de la incógnita. Se escriben como: 
$$ax^2 + bx + c = 0$$
- la incógnita es $x$,
- los coeficientes $a, b, c$ son [[Números reales]], y 
- $a$ es diferente de cero.

las soluciones de la ecuación cuadrática son los puntos en los que corta al eje X en una gráfica.

![[ATL_cuadraticasgrafico.png]]
- hay ecuaciones con dos respuestas o dos raíces
- hay ecuaciones con una respuesta o una raíz
- hay ecuaciones sin una respuesta _real_

### cómo resolver ecuaciones cuadráticas

la _fórmula de Bashkara_ o fórmula resolvente para encontrar las soluciones a todas las ecuaciones cuadráticas es: $$x_1,_2=\frac{-b±\sqrt{b^2-4ac}}{2a}$$
Pero hay otras formas de resolver las ecuaciones:
- [[Factor común]]
- Trinomio de $x^2+bx+c$
- Trinomio de $ax^2+bx+c$
- Trinomio cuadrado perfecto
- Diferencia de cuadrados

### discriminante
el discriminante se refiere a la expresión $b^2-4ac$, se simboliza con la letra griega _∆_.

si el discriminante es _mayor a cero_, se dice que hay **dos soluciones reales y diferentes**.
$$x_1=\frac{-b+\sqrt{∆}}{2a} \;\;\;\; x_2=\frac{-b-\sqrt{∆}}{2a}$$

si el discriminante es _igual a cero_, se dice que hay **dos soluciones reales iguales**, o una **única raíz real doble**. se dice "doble" porque como el determinante es cero no importa el signo, la ecuación termina igual.
$$x_1,_2=\frac{-b±\sqrt{0}}{2a} = \frac{-b}{2a}$$

si el discriminante es _menor a cero_, se dice que hay **no hay solución real**. La solución está en el campo de los [[números complejos]], ya que el cuadrado de un número real no puede ser negativo, y por lo tanto no existen raíces cuadradas para los números negativos.
$$x_1,_2=\frac{-b±\sqrt{-∆}}{2a}$$

### propiedades de las raíces
si $∆≥0$ entonces sumar las raíces nos da como resultado
$$
\begin{align}

x_1+x_2 & =\left(\frac{-b+\sqrt{∆}}{2a}\right)+\left(\frac{-b-\sqrt{∆}}{2a}\right)\\

& = \frac{-b+\sqrt{∆}-b-\sqrt{∆}}{2a}=\frac{-2b}{2a}=\frac{-b}{a}
\end{align}
$$

…por lo tanto, podemos decir que $$\boxed{x_1+x_2=\frac{-b}{a}}$$
***
por otro lado, si multiplicamos las raíces obtenemos
$$
\begin{align}

x_1·x_2 & =\left(\frac{-b+\sqrt{∆}}{2a}\right)·\left(\frac{-b-\sqrt{∆}}{2a}\right)\\

& = \frac{(-b)(-b)+(-b)(-\sqrt{∆})+(-b)\sqrt{∆}+\sqrt{∆}(-\sqrt{∆})}{(2a)^2}\\

& = \frac{b^2+b\sqrt{∆}-b\sqrt{∆}-(\sqrt{∆})^2}{4a^2}\\

& = \frac{b^2-∆}{4a^2} = \frac{b^2-b^2+4ac}{4a^2} = \frac{4ac}{4a^2} = \frac{c}{a}

\end{align}
$$
…por lo que podemos decir que $$\boxed{x_1·x_2=\frac{c}{a}}$$

si $∆<0$ entonces se obtiene la misma relación en ambos casos. %%no tengo ganas de escribir el cálculo%% sabiendo estas relaciones podemos escribir la ecuación cuadrática de forma más simple y en muchos casos conveniente.

si reescribimos $ax^2 + bx + c = 0$ como
$$a \left(x^2+\frac{b}{a}x+\frac{c}{a}\right) = 0$$
…aparecen las expresiones $\frac{b}{a}$ y $\frac{c}{a}$, que como vimos son iguales a
$$\frac{b}{a}=-(x_1+x_2) \;\;\;\; \frac{c}{a}=x_1·x_2$$
…por lo que podemos reemplazarlas:
$$
\begin{align}

a \left(x^2+\frac{b}{a}x+\frac{c}{a}\right) & = a \left(x^2-(-\frac{b}{a})x+\frac{c}{a}\right) = 0\\

& = a(x^2-(x_1+x_2)x+(x_1·x_2))\\

& = a(x_2-xx_1-xx_2+x_1·x_2)\\

& = a(x(x-x_1)-x_2(x-x_1))\\

\end{align}
$$
y como $(x-x_1)$ es un factor común, resulta en
$$\boxed{a(x-x_1)(x-x_2)=0}$$

