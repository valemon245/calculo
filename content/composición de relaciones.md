---
Created: 2024-03-30
---

>[!abstract] definición
>teniendo tres [[conjunto|conjuntos]] $A,B,C$ y dos [[relación binaria|relaciones]] $R\subset A\times B$ y $S\subset B\times C$, $S\circ R$ es un subconjunto de $A\times C$.

para que un par ordenado $(x,z)$ pertenezca a $S\circ R$, debe haber un $y$ que sea el segundo elemento de un par ordenado con $x$ en $R$ y el primer elemento en un par ordenado con $z$ de $S$. si no existe esta $y$ que cumpla con las condiciones, entonces $S\circ R=\varnothing$.

simbólicamente, $S\circ R\subset A\times C/(x,z)\in(S\circ R)\Leftrightarrow\exists y\in B/(x,y)\in R\wedge(y,z)\in S$.

![[alg_composicion-relaciones2.png|550]]

>[!caution] importante
>$S\circ R$ no es lo mismo que $R\circ S$. se escriben en el orden inverso al que se realizan las operaciones. 
>
>$R\circ S$ sería un subconjunto de $C\times A$.

un ejemplo: tenemos los conjuntos $A=\{ 1,2,3,4,5 \}$, $B=\{ 1,4,6,16 \}$ y $C=\{ 2,3,8,10 \}$ junto a las relaciones $R\subset A\times B:(x,y)\in R\Leftrightarrow y= x^{2}$ y $S\subset B\times C:(y,z)\in S\Leftrightarrow z=\frac{y}{2}$.

![[alg_composicion-relaciones.png|500]]

para funciones, ver [[composición de funciones]].