---
Created: 2024-04-21
aliases:
  - principio de inducción
  - inducción
  - PIC
---
# principio de inducción
#números #matematica 

>[!abstract] definición
>razonamiento que demuestra que una [[proposición lógica|proposición]], dependiente de una variable $n$ que toma infinidad de valores [[números naturales|naturales]], siempre es verdadera.

el principio de inducción matemática se suele comparar con el *efecto dominó*: asumiendo que están todos separados por la misma distancia, si el primer dominó cae y al caer tumba al segundo dominó, podemos afirmar que todas las fichas siguientes también caerán.

![[alg_efecto dominó.png|500]]

## pasos de la inducción
queremos verificar que una [[función proposicional]] $P(n)$ es verdadera para todos los $n\in\mathbb{N}$. para demostrar esto por inducción, podemos distinguir tres pasos:
1. **paso base**: demostramos que $P(1)$ es verdadera.
	- siguiendo la analogía de antes, probamos que el primer dominó se cae.
2. **paso inductivo (hipótesis)**: suponemos que $P(h)$ es verdadera. a esto le llamamos nuestra **hipótesis inductiva**, y va a ser de utilidad en el siguiente paso.
3. **paso inductivo (tesis)**: demostramos que $P(h+1)$ es verdadera. a esto le llamamos nuestra **tesis inductiva**.
	- probamos que las siguientes fichas del dominó también caen.

si todos los pasos se logran, podemos afirmar que $\forall n\in\mathbb{N}: P(n)$.

## demostración
la demostración de la tesis inductiva siempre es el paso más complicado. el proceso dependerá de la proposición, de los conocimientos sobre propiedades que tengamos y de cómo usemos la hipótesis inductiva a nuestro favor.

ver [[ej_inducción]].

## por qué principio de inducción completa?
el principio de inducción sirve principalmente para demostrar propiedades en los números naturales, sin tener que probar muchos o infinitos casos de valores particulares.