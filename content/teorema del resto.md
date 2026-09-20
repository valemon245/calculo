---
Created: 2024-06-21
---
# teorema del resto

>[!abstract] definición
>teorema que dice que el resto de dividir un [[polinomio]] por otro de forma $(x-b_{0})$ es igual a la [[especialización de un polinomio|especialización]] del dividendo por $b_{0}$.

es decir, $R(x)=P(b_{0})$.
- recordemos que en este caso especial, $R(x)$ es de grado 0.

## demostración
usando el [[algoritmo de la división]], tenemos que:
$$  
\begin{aligned}  
P(x) &= Q(x)\cdot C(x)+R \  
P(x) &= (x-b_{0})\cdot C(x)+R \  
P(b_{0}) &= (b_{0}-b_{0})\cdot C(b_{0})+R \  
P(b_{0}) &= 0\cdot C(b_{0})+R \  
P(b_{0}) &= 0+R=R  
\end{aligned}  
$$
