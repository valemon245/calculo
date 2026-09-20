---
Created: 2024-03-29
---
# operaciones entre conjuntos
#lógica #conjuntos 

>[!abstract] definición
>símbolos que conectan [[conjunto|conjuntos]] para crear otros conjuntos.

| símbolo                   | nombre                                                      | simbolización                                                                                                                                                                       |
| ------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $\cup$                    | [[unión de conjuntos\|unión]]                               | $A\cup B=\left\{ x/x\in A\vee x\in B\right\}$                                                                                                                                       |
| $\cap$                    | [[intersección de conjuntos\|intersección]]                 | $A\cap B=\left\{ x/x\in A\wedge x\in B\right\}$                                                                                                                                     |
| $-$                       | [[diferencia de conjuntos\|diferencia]]                     | $A-B=\left\{ x/x\in A\wedge x\notin B\right\}$<br>$A-B=A\cap B^{c}$                                                                                                                 |
| $X^{c}$<br>$\overline{X}$ | [[complemento de un conjunto\|complemento]]                 | $\overline{A}=\mathcal{U}-A=\left\{ x/x\in \mathcal{U}\wedge x\notin A\right\}=\{x\notin A\}$<br>$A^{c}=\left\{x\in\mathcal{U}:x\notin A\right\}=\mathcal{U}-A$                     |
| $\triangle$               | [[diferencia simétrica de conjuntos\|diferencia simétrica]] | $$\begin{align}A\triangle B & =\left\{ x/x\in A\veebar x\in B\right\} \\& =\left( A\cup B\right) -\left( A\cap B\right) \\& =\left( A-B\right) \cup \left( B-A\right) \end{align}$$ |

a veces es más facil ver lo que hace cada operación con un [[diagrama de venn]]:
![|500](https://i.postimg.cc/fL0rrGRJ/ezgif-3-8d6e61c959.gif)

## propiedades de las operaciones entre conjuntos
similares a las [[proposiciones equivalentes|propiedades de las proposiciones]].

| nombre                                     | simbolización                                                                                                                                                        |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| involución o doble complemento             | $\overline{\overline{A}} = A$<br>$(A^{c})^{c}=A$                                                                                                                     |
| conmutativa                                | $A\cup B= B\cup A$<br>$A\cap B= B\cap A$                                                                                                                             |
| asociativa                                 | $A\cup \left( B\cup C\right) = \left( A\cup B\right) \cup C$<br>$A\cap \left( B\cap C\right) = \left( A\cap B\right) \cap C$                                         |
| distributiva                               | $A\cup \left( B\cap C\right) = \left( A\cup B\right) \cap \left( A\cup C\right)$<br>$A\cap \left( B\cup C\right) = \left( A\cap B\right) \cup \left( A\cap C\right)$ |
| idempotencia                               | $A\cup A= A$<br>$A\cap A= A$                                                                                                                                         |
| de Morgan                                  | $\overline{A\cup B} = \overline{A} \cap \overline{B}$<br>$\overline{A\cap B} = \overline{A} \cup \overline{B}$                                                       |
| dominancia                                 | $A\cup \mathcal{U}=\mathcal{U}$<br>$A\cap \varnothing=\varnothing$                                                                                                   |
| elemento neutro                            | $A\cup \varnothing= A$<br>$A\cap \mathcal{U}= A$                                                                                                                     |
| absorción                                  | $A\cup(A\cap B)= A$<br>$A\cap (A\cup B)= A$                                                                                                                          |
| equivalencia de la diferencia              | $A-B=A\cap \overline{B}$                                                                                                                                             |
| complementarios                            | $A\cap \overline{A}=\varnothing$<br>$A\cup \overline{A}= \mathcal{U}$                                                                                                |
| complemento del conjunto vacío y universal | $\varnothing ^{c}=\mathcal{U}$<br>$\mathcal{U}^{c}=\varnothing$                                                                                                      |
