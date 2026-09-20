---
Created: 2024-03-29
---
# notación por comprensión

>[!abstract] definición
>una forma de representar un [[conjunto]], donde se definen las propiedades que deben satisfacer los elementos para ser parte del mismo.

existen dos formas de esta notación.

a una se la puede llamar **“[[dominio de la relación|dominio]]/filtro”**: primero se establece el [[conjunto universal]] de donde se toman los posibles elementos, y luego se escribe una [[función proposicional]] que los filtra para dejar solo los elementos que queremos en nuestro conjunto.
- esta forma es útil cuando *la propiedad que tenemos se puede escribir en forma de una [[proposición lógica|proposición]].*
- $\{x\in\mathbb{N}:x^2<100\}$ toma el conjunto de los [[números naturales]] y filtra todos los números cuyo cuadrado sean menores a 100. nos deja con $\{ 1,2,3,4,5,6,7,8,9 \}$.

a la otra se la puede llamar **“fórmula/dominio”**: en esta, primero describimos una fórmula, y luego un conjunto universal al que la vamos a aplicar, y cuyo resultado serán los elementos de nuestro conjunto.
- esta forma es útil cuando *nuestros elementos pueden ser representados con construcciones matemáticas.*
- $\{ x^{2}:x \in \mathbb{N} \}$ toma la fórmula $x^{2}$ y la aplica sobre todos los números naturales, dejándonos con el conjunto $\{ 1,4,9,16,25,36,49,\dots \}$.

estas son formas *incorrectas* de escribir un conjunto por comprensión:
- *predicado primero, luego dominio*: $\{x<2:x\in\mathbb{Z}\}$ no tiene sentido matemático porque no sigue la sintáxis de la notación por comprensión.
- *conjunto primero, luego fórmula*: $\{x\in\mathbb{Z}:x+2\}$ tampoco tiene sentido matemático.
