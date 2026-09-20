---
Created: 2024-03-29
---
# principio de inclusión y exclusión

>[!abstract] definición
>principio que permite calcular el [[cardinal de un conjunto|cardinal]] de la [[unión de conjuntos|unión]] o [[intersección de conjuntos|intersección]] de dos o más conjuntos usando otros cardinales.

conociendo el cardinal de dos conjuntos y el cardinal de su intersección, podemos *hallar el cardinal de su unión*. 

similarmente, conociendo el cardinal de dos conjuntos y de su unión, podemos *hallar el cardinal de su intersección*.

simbólicamente, esto se representa como:
- $\#(A\cup B)=\# A + \# B- \#(A\cap B)$
- $\#(A\cap B)=\# A + \# B- \#(A\cup B)$
- $\#(A\cup B\cup C)=\# A + \# B + \# C-\# (A\cap B)-\# (A\cap C)-\# (B\cap C) + \#(A\cap B\cap C)$
- $\#(A\cap B\cap C)=\#(A\cup B\cup C) -\# A - \# B - \# C+\# (A\cup B)+\# (A\cup C)+\# (B\cup C)$

un ejemplo: sabemos que $\# A=15$, $\# B=20$ y $\# (A\cup B)=26$.
- si queremos saber el cardinal de $A\cap B$, entonces calculamos $15+20-26=9$.

## por qué principio de inclusión y exclusión?
el principio de inclusión y exclusión nos permite resolver ciertos problemas matemáticos.