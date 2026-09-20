---
Created: 2024-03-29
---
# igualdad de conjuntos

>[!abstract] definición
>propiedad que dice que si un [[conjunto]] $A$ está [[relación de inclusión|incluído]] en un conjunto $B$ y $B$ está incluído en $A$, entonces $A$ y $B$ son iguales.

simbolizado, $A=B \Leftrightarrow A\subset B \wedge A\subset B$.

un ejemplo de esto: tenemos los conjuntos $A=\left\{1,3\right\}$ y $B=\left\{n:n^2-4\cdot n=-3\right\}$. podemos afirmar que $A\subset B$ ya que 1 y 3 satisfacen la propiedad establecida en el conjunto $B$. 

ahora, probemos que $B\subset A$ y por lo tanto $A=B$. tomemos un elemento genérico $n$ de $B$:
$$\begin{aligned}n\in B\quad&\Rightarrow n^2-4\cdot n=-3\\&\Rightarrow n^2-4\cdot n+3=0\\\\&\Rightarrow n=\frac{-(-4)\pm\sqrt{(-4)^2-4\cdot1\cdot3}}{2\cdot1}\\\\&\Rightarrow n=\frac{4\pm\sqrt{16-12}}2\\\\&\Rightarrow n=\frac{4\pm\sqrt4}2\\\\&\Rightarrow n=\frac{4\pm2}2\\\\&\Rightarrow n\in A\end{aligned}$$

