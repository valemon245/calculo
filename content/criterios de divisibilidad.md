---
Created: 2024-06-10
---
# criterios de divisibilidad
#números 

>[!abstract] definición
>formas rápidas de saber si un [[números enteros|número entero]] es [[divisibilidad de los enteros|divisible]] por otro.

teniendo $x\in\mathbb{Z}$, podemos decir que:
- es divisible por 2 si termina en una cifra [[enteros pares e impares|par]].
- es divisible por 3 si la suma de sus dígitos es divisible por 3.
- es divisible por 4 si el doble de las decenas más las unidades es divisible por 4.
	- alternativamente, es divisible por 4 si sus dos últimas cifras son 0 o divisibles por 4.
		- nota: *no se suman los dígitos*.
- es divisible por 5 si termina en 0 o 5.
- es divisible por 6 si es divisible por 2 y 3.
- es divisible por 7 si, al quitar la última cifra del número y restarle el doble de esa cifra que quitamos, nos queda un nro. divisible por 7.
- es divisible por 8 si las últimas tres cifras son 0 o divisibles por 8.
	- nota: *no se suman los dígitos*. si tenemos 8390, hay que verificar que 390 sea divisible por 8.
- es divisible por 9 si la suma de sus dígitos es divisible por 9.
- es divisible por 10 si termina en 0.
- es divisible por 11 si $(\text{suma de digitos en posiciones pares})-(\text{suma de digitos en posiciones impares})$ es divisible por 11.

## ejemplo
queremos saber si 43755 es divisible por 7. aplicando el criterio de divisibilidad, vemos que:
- $4375-2\cdot 5=4365$
- $436-2\cdot 5= 426$
- $42-2\cdot 6=30$
- 30 no es divisible por 7, por lo que 43755 tampoco.