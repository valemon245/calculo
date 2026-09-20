---
Created: 2024-06-24
---
# regla de laplace

>[!abstract] definición
>fórmula para calcular el [[determinante de una matriz]] de orden igual o mayor a 3.

la regla de laplace descompone el hallar el determinante de una matriz $A$ en cálculos de determinantes para matrices de menor orden. 

antes de usar la fórmula, elegimos una fila (o columna) de nuestra matriz para desarrollar. es conveniente elegir la que tenga más ceros, ya que acorta el cálculo.

una vez tenemos nuestra elección, definimos la regla de laplace como:
$$ |A| = \sum_{j=1}^n a_{ij}\cdot (-1)^{i+j}\cdot \Big|A_{(i,j)}\Big|,\;\;con\:1\leq i\leq n$$
- $A_{(i,j)}$ es la [[matriz adjunta de un elemento]].

usando la regla de laplace podemos llegar a determinantes que se pueden calcular usando otras reglas, como la [[regla de sarrus]].

## relacionado
- $\Big|A_{(i,j)}\Big|$ es el [[menor complementario]].
- $(-1)^{i+j}\cdot \Big|A_{(i,j)}\Big|$ es el [[cofactor]].