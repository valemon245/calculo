---
Created: 2024-03-29
---
# partición de un conjunto

>[!abstract] definición
>una colección de subconjuntos no vacíos de un [[conjunto]] $A$ que unidos forman al conjunto $A$ original, sin superposiciones y sin elementos adicionales.

en otras palabras, teniendo un conjunto $A\neq \varnothing$, $P$ es una partición de $A$ si y sólo si está formada por subconjuntos $A_1, A_{2}, A_3\dots A_{n}$ que cumplen 3 condiciones:
- $\Leftrightarrow A_i\neq \varnothing \;\; \forall i$ 
	- ningún subconjunto está [[conjunto vacío|vacío]].
- $\Leftrightarrow A_i\cap A_{j} = \varnothing \;\; \forall i\neq j$ 
	- la intersección entre cualquier par de subconjuntos debe ser vacía. es decir, deben ser [[conjuntos disyuntos]].
- $\Leftrightarrow \cup A_i= A$ o bien $\Leftrightarrow \forall x \in A:\exists A_{i} \in P:x \in A_{i}$
	- cada elemento de $A$ debe existir en algún subconjunto de $P$.

las particiones están incluídas en el [[conjunto de partes]] de $A$. los subconjuntos $A_i$ se llaman **celdas de la partición**.

por ejemplo, tenemos el conjunto $A=\{a,b,c,d,e\}$
- $P_1= \{\{a,b,c\},\{d,e\}\}$ 
	- ✅ sí es una partición.
- $P_2= \{\{a,b\},\{c,d\},\{b,e\}\}$ 
	- ⛔ la intersección de las celdas no es vacía.
- $P_3= \{\{a,b\},\{c\},\{e\}\}$ 
	- ⛔ falta la $d$.
- $P_4= \{\{a\},\{b\},\{c\},\{d,e\}\}$ 
	- ✅ sí es una partición.
- $P_5= \{\{a\},\{b,c,d\},\{\;\},\{e\}\}$ 
	- ⛔ tiene una celda vacía.

ahora veamos posibles particiones de $\mathbb{R}$ ([[números reales]]):
- $\begin{align}& A_{1}=(-\infty ; -2] \\& A_{2}=(-2;0] \\& A_{3}=(1;+\infty) \end{align}$ 
	- ⛔ no tenemos los números entre $0$ y $1$.
- $\begin{align}& A_{1}=(-\infty ;-1) \\& A_{2}=\{-1,-2\} \\& A_{3}=(-1;+\infty) - \{2\} \end{align}$ 
	- ✅ sí es una partición de $\mathbb{R}$.
- $\begin{align}& A_{1}=(-\infty ;-3] \\& A_{2}=(-3;0) \\& A_{3}=\mathbb{R}^+ \end{align}$ 
	- ⛔ no está el $0$.
- $\begin{align}& A_{1}=(-\infty ;4) \\& A_{2}=\{0,5\} \\& A_{3}=[4;+\infty )-\{5\} \end{align}$ 
	- ⛔ el 0 está en $A_1$ y en $A_2$.
