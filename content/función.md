---
Created: 2024-03-30
---
# función

>[!abstract] definición
>una [[relación binaria|relación]] que asocia los elementos de un [[conjunto]] (entrada) a los elementos de otro conjunto (salida), de tal forma que a cada entrada se le asigna exactamente una sola salida.

hay muchas formas de definir una función. la más corta podría ser que una función *relaciona a una entrada con una salida*.

llamemos a la función $f$. entonces, tenemos lo siguiente:
$$\Huge f(\textcolor{red}{\underset{\text{entrada}}{x}})=\textcolor{blue}{\underset{\text{lo que debe ser la salida}}{x^{2}}}$$

la función $f$ toma la **entrada** $x$ y aplica una **relación** sobre ella (elevar al cuadrado). el resultado será nuestra **salida**.
- por ejemplo, $f(\textcolor{red}{5})=\textcolor{blue}{25}$.

a veces, la función no tiene nombre. en ese caso, podemos ver algo como:
$$\Huge \textcolor{blue}{\underset{\text{salida}}{y}}=\textcolor{red}{\underset{\text{entrada+relacion}}{x^{2}}}$$

la idea es similar. la **salida** $y$ es igual a la **entrada** $x$ al cuadrado (la **relación**).

pero qué elementos podemos usar en una función? hay que definir un conjunto del cual tomar nuestros elementos de entrada.

## aplicando la [[teoría de conjuntos MOC|teoría de conjuntos]]
todas las funciones son relaciones, pero no todas las relaciones son funciones. para que una relación sea una función, debe cumplir dos condiciones:

la **condición de existencia**, que dice que para todo elemento del conjunto $A$ existe un elemento del conjunto $B$. 
- simbólicamente, $\forall x\in A,\exists y\in B/(x,y)\in f$

la **condición de unicidad**, que dice que este elemento de $B$ tiene que ser *único*, uno solo.
- simbólicamente, $(x,y)\in f\wedge(x,z)\in f\Rightarrow y=z$ 

>[!caution] cuando decimos *único* nos referimos a que a cada elemento $x$ le corresponde *una sola imagen*. varios elementos $x$ pueden compartir una $y$.

una función, entonces, es una relación entre $A$ y $B$ donde a cada elemento $x$ de $A$ le corresponde un único elemento $y$ de $B$.

simbólicamente, sea $f:A\to B$ decimos que $f$ es una función si $\forall x\in A,\exists!\:y\in B/\:y=f(x)$.
- esta fórmula unifica las fórmulas de las dos condiciones en una.

## pares ordenados
como ya sabemos, una relación es un conjunto de [[par ordenado|pares ordenados]], y las funciones no son excepción. en este caso, se escriben como $(entrada,salida)$.

el beneficio de los pares ordenados es que podemos graficarlos, ya que también funcionan como coordenadas.

>[!tip] muchos nombres!
>las partes de una función se pueden hallar con varios nombres. usemos $f(x)$ de ejemplo:
>
>##### entrada: $x$
>- [[dominio de la relación|dominio]]
>- elementos del dominio
>- variable independiente
>- argumento
>
>##### relación: $f()$
>- regla
>- propiedad
>
>##### salida: $f(x)$ (o lo que sea igual a $f(x)$)
>- [[imagen de la relación|imagen]] o rango
>- elementos de la imagen/rango
>- variable dependiente
>- valor de la función

## conceptos relacionados
- [[clasificación de funciones]]
- [[función lineal]]
- [[función cuadrática]]
- [[composición de funciones]]
- funciones especiales:
	- [[función parte entera]]
	- [[función módulo]]
	- [[función factorial]]
	- [[función característica]]
- [[ej_función|ejemplos y ejercicios]]

## por qué función?
la función es un concepto muy usado a lo largo de la matemática, física, ingeniería, ciencias de la computación, entre otros.

