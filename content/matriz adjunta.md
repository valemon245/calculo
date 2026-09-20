---
Created: 2024-06-24
aliases:
  - adjunta de una matriz
  - adjunta
---
# matriz adjunta de una matriz

>[!abstract] definición
>teniendo una [[matriz cuadrada]] $A$, la traspuesta de la [[matriz]] que se obtiene reemplazando cada elemento de $A$ por su [[cofactor]] o adjunto.

>[!caution|minimal] 
>algunas fuentes usan “matriz adjunta” para referirse a la matriz de cofactores _sin_ ser traspuesta.

denotada con $Adj(A)$, podemos definirla como:
$$  
Adj(A)=  
\begin{bmatrix}  
A_{11} & A_{12} & \dots & A_{1n} \  
A_{21} & A_{22} & \dots & A_{2n} \  
\vdots & \vdots & \dots & \vdots \  
A_{n1} & A_{n2} & \dots & A_{nn}  
\end{bmatrix}_{n\times n}^{T}  
$$
- $A_{ij}$ representa el cofactor de $a_{ij}$ en $A$. no confundir con la [[matriz adjunta de un elemento]].
- alternativamente, se puede denotar $cof(A)^{T}$.

## ejemplo
teniendo la matriz $A=\begin{bmatrix}2&1&1\\3&4&1\\5&0&1\end{bmatrix}$, decimos que:
$$Adj(A)=\begin{bmatrix}\begin{vmatrix}4&1\\0&1\end{vmatrix}&-\begin{vmatrix}3&1\\5&1\end{vmatrix}&\begin{vmatrix}3&4\\5&0\end{vmatrix}\\-\begin{vmatrix}1&1\\0&1\end{vmatrix}&\begin{vmatrix}2&1\\5&1\end{vmatrix}&-\begin{vmatrix}2&1\\5&0\end{vmatrix}\\\begin{vmatrix}1&1\\4&1\end{vmatrix}&-\begin{vmatrix}2&1\\3&1\end{vmatrix}&\begin{vmatrix}2&1\\3&4\end{vmatrix}\end{bmatrix}^T=\begin{bmatrix}4&2&-20\\-1&-3&5\\-3&1&5\end{bmatrix}^T=\begin{bmatrix}4&-1&-3\\2&-3&1\\-20&5&5\end{bmatrix}$$

si la dividiéramos por el [[determinante de una matriz|determinante]] de $A$ obtendríamos su [[inversa de una matriz|matriz inversa]], asumiendo que $A$ es inversible.