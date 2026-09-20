---
Created: 2024-03-10
aliases:
  - condicional
  - implicación
---
# implicación lógica o condicional

>[!abstract] definición
>un [[conectivos lógicos|conector lógico]] que equivale a decir “$p$ implica $q$” o “si $p$ entonces $q$”.

la mejor forma de entender una implicación o condicional es a través de un ejemplo. 

ana le dice a lucas: “si aprobás el examen, entonces te presto mi apunte”. esta es la implicación de dos proposiciones.
- $p$: lucas aprueba el examen → **antecedente** o **hipótesis**
- $q$: ana le presta el apunte a lucas → **consecuente** o **tesis**

para decidir la veracidad de un condicional se lo puede pensar como un *compromiso o promesa*, y su valor de verdad va a depender en el cumplimiento de tal.
- si lucas aprueba el exámen ($p=V$) y ana le presta su apunte ($q=V$), se cumplió la promesa. $\boxed{p\Rightarrow q=V}$ 
- si lucas aprueba el exámen ($p=V$) pero ana no le presta su apunte ($q=F$), ana no cumplió con la promesa. $\boxed{p\Rightarrow q=F}$ 
- si lucas no aprueba el exámen ($p=F$) se podría decir que ana está liberada de su compromiso, ya que no hablaron de que harían si lucas no aprobaba. aunque ana le de su apunte igualmente ($q=V$) o no ($q=F$), el compromiso se cumple. $\boxed{p\Rightarrow q=V}$ 
$$\begin{array}{|c|c|c|}\hline p&q&p\Rightarrow q\\\hline\text{V}&\text{V}&\text{V}\\\text{V}&\text{F}&\text{F}\\\text{F}&\text{V}&\text{V}\\\text{F}&\text{F}&\text{V}\\\hline\end{array}$$

sin importar la realidad de la frase que estemos analizando, si el antecedente de un condicional es falso, la proposición siempre es verdadera porque el antecedente falso significa que la condición inicial no se da en absoluto. 

la forma en la que funciona el condicional se relaciona con la ciencia deductiva, ya que en el razonamiento matemático no se puede deducir una proposición falsa de una proposición verdadera ($p(V) \Rightarrow q(F) = F$), pero si se puede deducir una proposición verdadera o falsa a partir de una proposición falsa.

en un condicional, $p$ es [[condición suficiente y condición necesaria|suficiente]] para $q$ y $q$ es [[condición suficiente y condición necesaria|necesario]] para $p$.

de una implicación podemos obtener [[implicaciones asociadas]], así como una forma de [[negación de una implicación|negarla]].

>[!tip]- estructura de una implicación
>es ideal tener una frase de estructura “*si… entonces…*” para realizar el análisis lógico. si podemos cambiar nuestra declaración a esto, mejor.
>
>##### ejemplo 1:
>- *para* reservar en este hotel *es suficiente* con dar el nombre y número de visa. →
>- es *suficiente* con dar el nombre y número de visa *para* reservar en este hotel. →
>	- $p$: dar el nombre y número de visa.
>	- $q$: reservar en este hotel.
>- *basta* con dar el nombre y número de visa *para* reservar en este hotel. →
>- *si* das el nombre y número de visa *entonces* puedes reservar en este hotel.
>
>##### ejemplo 2:
>- la derivabilidad en un punto *es condición suficiente para* que la función sea continua en el punto. →
>- es *suficiente* que la función sea derivable en un punto *para* que sea continua en el punto. →
>	- $p$: la funcion es derivable en un punto.
>	- $q$: la función es continua en el punto.
>- *basta* con que la función sea derivable en un punto *para* que sea continua en el punto. →
>- *si* una función es derivable en un punto *entonces* es continua en el punto.

