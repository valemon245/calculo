---
Created: 2024-06-21
---
# división de complejos

>[!abstract] definición
>reglas para la operación de división en el conjunto de [[números complejos]].

tenemos $z=(a,b)$ y $w=(c,d)$ tal que $w\neq(0,0)$. para dividir dos números complejos, multiplicamos el cociente de ambos por el [[complejos conjugados|conjugado]] de $w$.

$$\frac{z}{w}=\frac{z\cdot\overline{w}}{w\cdot\overline{w}}=\frac{a+bi}{c+di}\cdot\frac{c-di}{c-di}=\frac{(a+bi)\cdot(c-di)}{c^2+d^2}=\frac{ac+bd}{c^2+d^2}+\frac{bc-ad}{c^2+d^2}i$$

## ejemplo
tenemos $z=-2+3i$ y $w=1-2i$:

$$  
\begin{align}  
\frac{-2+3i}{1-2i}  
&= \frac{-2+3i}{1-2i}\cdot\frac{1+2i}{1+2i} \  
&= \frac{(-2-6)+(-4+3)i}{1^2+2^2} \  
&= \frac{-8}{5}-\frac{1}{5}i  
\end{align}  
$$

