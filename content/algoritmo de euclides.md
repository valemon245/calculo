---
Created: 2024-06-20
---
# algoritmo de euclides

>[!abstract] definición
>algoritmo para hallar el [[máximo común divisor]] de dos [[números enteros]].

teniendo $a,b\in\mathbb{Z}$ siendo $b\neq 0$, podemos hallar $mcd(a,b)$ de la siguiente forma:

$$\large\begin{aligned}
&a=b\cdot q + r, \; 0< r\leq |b| \\
&b=r\cdot q_{2} + r_{2}, \; 0< r_{2}\leq |r| \\
&r=r_{2}\cdot q_{3} + r_{3}, \; 0< r_{3}\leq |r_{2}| \\
&r_{2}=r_{3}\cdot q_{4} + r_{4}, \; 0< r_{4}\leq |r_{3}| \\
&\dots\dots\dots\\
&r_{n-2}=r_{n-1}\cdot q_{n-1} + r_{n}, \; 0< r_{n}\leq |r_{n-1}| \\
&r_{n-1}=r_{n}\cdot q_{n} + r_{n+1}, \; r_{n+1} = 0 
\end{aligned}$$

es decir, se itera el [[algoritmo de la división]] hasta que el resto sea igual a 0. cuando ocurre, podemos decir que $mcd(a,b)=r_{n}$.

## ejemplo
digamos que queremos hallar $mcd(725,441)$:
$$\begin{aligned}
&725=441\cdot 1 + 284 \\
&441=284\cdot 1 + 157 \\
&284=157\cdot 1 + 127 \\
&157=127\cdot 1 + 30 \\
&127=30\cdot 4 + 7 \\
&30=7\cdot 4 + 2 \\
&7=2\cdot 3 + 1 \\
&2=1\cdot 2
\end{aligned}$$

…por lo tanto, $mcd(725,441)=1$. podemos decir que 725 y 441 son [[enteros coprimos]].