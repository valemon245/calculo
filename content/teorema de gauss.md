#polinomios 

>[!abstract] definición
>teorema que asegura que, si un [[polinomio]] real $P$ con coeficientes enteros tiene [[raíz de un polinomio|raíces]] [[números racionales|racionales]] (se pueden escribir como $\frac{p}{q}$), se verifica que:
>- $p$ es un divisor de $a_0$,
>- $q$ es un divisor de $a_n$,
>- $p$ y $q$ son [[enteros coprimos|coprimos]].

en un sentido práctico, el teorema de gauss es un atajo para hallar posibles raíces de $P$. 

teniendo un polinomio de grado $n$ tal que:
$$P(x)=a_nx^n+a_{n-1}x^{n-1}+\dots+a_2x^2+a_1x+a_0$$

…una o más raíces podrían ser un cociente entre un divisor de $a_0$ y un divisor de $a_n$.

una vez hallamos los divisores de ambos y los cocientes que se pueden formar, solo queda probar cada uno y ver si son o no raíces, ya sea usando [[regla de ruffini|ruffini]] o [[especialización de un polinomio|especializando]] la indeterminada de $P$.

nótese que siempre cabe la posibilidad de que no hayan raíces racionales, en cuyo caso el teorema de gauss no nos ayudará a hallar ninguna raíz.

