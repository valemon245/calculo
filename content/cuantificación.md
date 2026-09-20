---
Created: 2024-03-28
---

>[!abstract] definición
>proceso por el cual le asignamos un [[dominio de la relación|dominio]] a una función proposicional, para que esta última pueda tener un valor de verdad factual como una [[proposición lógica|proposición]].

ya que las [[función proposicional|funciones proposicionales]] no tienen un valor de verdad determinado, no se puede utilizar [[lógica proposicional MOC|lógica proposicional]] en ellas para trazar conclusiones. 

pero entonces que hacemos? para crear una proposición que pueda ser $V$ o $F$, debemos asignar valores a las variables de la función. 

por ejemplo, tenemos $P(x): x \text{ es par}$.
- asignamos $4$ a $x$; nos deja con la proposición $P(4): 4 \text{ es par}$, la cual es $V$.
- hacemos lo mismo con $-5$; ahora tenemos $P(-5): -5 \text{ es par}$, lo cual es $F$.

este no suele ser el método más efectivo, ya que muchas veces queremos saber el valor de una función proposicional sobre un rango más extenso de elementos.

para resolver este problema, asignamos un rango específico de elementos a las variables de la función usando la **cuantificación**. 

## cuantificadores
existen 2 tipos principales de cuantificadores:

### cuantificador universal
el **cuantificador universal** transforma a una función proposicional en una proposición que dice que *una propiedad es verdadera para todos los valores posibles de una variable dentro de un dominio*.

un cuantificador universal se suele hallar escrito como:
- $P(x)$ es verdadero para todos los valores de $x$.
- para todo $x$, $P(x)$.
- para cada $x$, $P(x)$.
- para cualquier $x$, $P(x)$.

simbólicamente, $\forall x \in A:P(x)$.
- nótese que usamos $:$ (“se verifica”). ver [[simbología matemática]].

### cuantificador existencial
el **cuantificador existencial** transforma a una función proposicional en una proposición que dice que *una propiedad es verdadera para algún valor posible de una variable dentro de un dominio*.

un cuantificador existencial se suele ver como:
- existe al menos un $x$ tal que $P(x)$
- para algunos $x$, $P(x)$
- hay un $x$ tal que $P(x)$

simbólicamente, $\exists x \in A/P(x)$.
- nótese que usamos $/$ (“tal que”).

#### cuantificador único
existe un tercer tipo menos usado de cuantificador para decir que *una propiedad es verdadera para un único valor de una variable dentro de un dominio*.

simbólicamente, $!\exists x \in A/P(x)$.

## negación de cuantificadores
recordemos que la [[negación lógica|negación]] de una proposición debe tener el valor de verdad opuesto.

para negar una cuantificación universal hay que poder afirmar que $P(x)$ *no se verifica para al menos uno de los valores posibles* dentro del dominio que le asignamos. 
- simbólicamente, $\neg(\forall x\in A,P(x))\equiv\exists x\in A,\neg P(x)$.

para negar una cuantificación existencial hay que poder afirmar que $P(x)$ *no se verifica para ninguno de los valores posibles* dentro del dominio asignado. 
- simbólicamente, $\neg(\exists x\in A,P(x))\equiv\forall x\in A,\neg P(x)$.

## por qué cuantificación?
la cuantificación nos permite obtener proposiciones lógicas de las funciones proposicionales, lo cual es útil para poder hacer deducciones lógicas.