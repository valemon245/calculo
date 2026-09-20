---
Created: 2024-06-10
---
# divisores
#números 

>[!abstract] definición
>siendo $a,b\in\mathbb{Z}$ y $b\neq 0$, caso especial donde la [[algoritmo de la división|división]] de $a$ por $b$ tiene resto 0.

si el resto de dividir $a$ por $b$ es cero, podemos decir que $b$ es **divisor** de $a$.
- simbólicamente, $b\mid a\Leftrightarrow\exists q\in\mathbb{Z}/a=q\cdot b$ o $a \text{ mod } b=0$.
- también se puede decir que $a$ **es múltiplo de** $b$.

## propiedades
siendo $a,b,c\in\mathbb{Z}$ donde $a\neq 0$, podemos decir que:

| coloquial                                                                       | simbólicamente                                                                               |
| ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| $a$ divide a sí mismo                                                           | $a\mid a$                                                                                    |
| $a$ divide a un nro. multiplicado por $a$                                       | $a\mid a\cdot c$                                                                             |
| $a$ divide a su opuesto y viceversa                                             | $a\mid -a$<br>$-a\mid a$                                                                     |
| $a$ divide a su valor absoluto y viceversa                                      | $a\mid \|a\|$<br>$\|a\| \mid a$                                                              |
| $1$ y $-1$ dividen a todos los nros.                                            | $1\mid a$<br>$-1\mid a$                                                                      |
| siendo $b\neq 0$, propiedad transitiva                                          | $b\neq 0:$<br>$a\mid b\wedge b\mid c\Rightarrow a\mid c$                                     |
| siendo $b\neq 0$, igualdad de $a$ y $b$                                         | $b\neq 0:$<br>$a\mid b\wedge b\mid a\Rightarrow a=b\vee a=-b$                                |
| si $a$ divide a 1 entonces es igual a 1/-1                                      | $a\mid 1\Rightarrow a=1\vee a=-1$                                                            |
| si $a$ divide a $b$ y $c$ entonces también divide a la suma/resta de ambos      | $a\mid b\wedge a\mid c\Rightarrow a\mid b+c$<br>$a\mid b\wedge a\mid c\Rightarrow a\mid b-c$ |
| si $a$ divide a $b$ y su suma con $c$ entonces también divide a $c$             | $a\mid b+c\wedge a \mid b\Rightarrow a\mid c$                                                |
| si $a$ divide a $b$ también divide a un nro. multiplicado por $b$               | $a\mid b\Rightarrow a\mid b\cdot c$                                                          |
| $a$ divide a $b$ si y solo sí divide a su valor absoluto                        | $a\mid b\Leftrightarrow a\mid \|b\|$                                                         |
| $a$ divide a $b$ si y solo sí su valor absoluto divide a $b$                    | $a\mid b\Leftrightarrow \|a\| \mid b$                                                        |
| $a$ divide a $b$ si y solo sí su valor absoluto divide al valor absoluto de $b$ | $a\mid b\Leftrightarrow \|a\| \mid \|b\|$                                                    |

## relacionados
- [[enteros pares e impares]]
- [[número primo]]
- [[criterios de divisibilidad]]
- [[máximo común divisor]]
- [[mínimo común múltiplo]]