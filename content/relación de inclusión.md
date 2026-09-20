---
Created: 2024-03-29
---
# relación de inclusión

>[!abstract] definición
>propiedad que dice que un [[conjunto]] $A$ está incluído en otro conjunto $B$ cuando todos los elementos de $A$ también pertenecen a $B$, representado con $\subset$.

simbólicamente, $A\subset B \Leftrightarrow \forall a: a \in A \Rightarrow a \in B$.

un elemento no puede estar “incluído” en un conjunto. para asociar conjuntos con sus elementos usamos la [[relación de pertenencia]].

digamos que tenemos $A=\{a, b,c,d,e\}$, $B=\{a, b, c\}$ y $C=\{2\}$
- $B\subset A$
- $C\not\subset A$
- $\{ a,b \} \subset B$ 

>[!faq] $\subset$ o $\subseteq$
>algunas fuentes no hacen diferencia ente ambos símbolos, otras dicen que $\subseteq$ permite la posibilidad de que $A=B$ mientras que $\subset$ no (inclusión estricta). 
>
>si $A\subset B$ pero $A$ y $B$ son distintos, podemos decir que $A\subsetneq B$.

## propiedades básicas de la inclusión
- todo conjunto está incluído en sí mismo. ($\forall A : A\subset A$)
- el [[conjunto vacío]] está incluído en todo conjunto. ($\forall A : \varnothing \subset A$) ^vacio
- todo conjunto está incluído en el [[conjunto universal]]. ($\forall A : A\subset \mathcal{U}$) ^universal
- **propiedad transitiva**; si $A$ está incluído en $B$ y $B$ está incluído en $C$ entonces $A$ está incluído en $C$. ($\forall A, B, C : A\subset B\wedge B\subset C\Rightarrow A\subset C$)

## por qué relación de inclusión?
la relación de inclusión asocia a los conjuntos con sus (sub)conjuntos.