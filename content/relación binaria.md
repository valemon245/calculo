---
Created: 2024-03-30
aliases:
  - relación
---
# relación
#lógica #conjuntos 

>[!emoji] ⭐ 
>tema de [[uni_algebra]]

>[!abstract] definición
>un [[conjunto]] de [[par ordenado|pares ordenados]] cuyos elementos, pertenecientes a otros dos conjuntos, están vinculados por una propiedad.

una relación siempre es el subconjunto de un [[producto cartesiano]]. si tenemos una relación $R$ entre los conjuntos $A$ y $B$, como los elementos de $R$ son pares ordenados al igual que en $A\times B$, podemos decir que $R\subset A\times B$.

simbólicamente, $R:A\to B\Leftrightarrow R\subset A\times B$.

un ejemplo: digamos que tenemos los conjuntos $A=\{2,3,9\}$ y $B=\{ 1,4,8 \}$, junto a la relación $R:A\to B/R=\{ (a,b)/a\leq b\}$
- $A\times B=\{(2,1),(2,4),(2,8),(3,1),(3,4),(3,8),(9,1),(9,4),(9,8)\}$
- $R=\{(2,4),(2,8),(3,4),(3,8)\}$

ahora veámoslo graficado en un [[diagrama de venn]]:
![[alg_relacion-venn.png|450]]

otras formas de representar gráficamente una relación:
- [[gráfico cartesiano]]
- [[matriz de adyacencia]]

## conceptos relacionados
- el [[dominio de la relación]], el conjunto de los primeros elementos de los pares en $R$.
- la [[imagen de la relación]], los segundos elementos de los pares en $R$. 
	- no siempre es igual al [[codominio]].
- la [[relación inversa]] de $R$.
- la [[composición de relaciones]].
- [[propiedades de relaciones definidas en un conjunto|propiedades]] y [[clasificación de relaciones definidas en un conjunto|clasificaciones]] de una relación incluída en $A^{2}$.
- las [[función|funciones]], un tipo especial de relación que es otro tema aparte.

## por qué relación matemática?
las relaciones son un tema fundamental de la [[teoría de conjuntos MOC|teoría de conjuntos]]. también es necesario saber de relaciones para aprender sobre funciones, que se utilizan mucho en diferentes ámbitos de matemática, física, ingeniería, ciencias de la computación, y otros.