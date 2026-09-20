---
Created: 2024-04-02
aliases:
  - función techo
  - función piso
  - función suelo
---
# función parte entera

>[!abstract] definición
>[[función]] que toma un [[números reales|número real]] como entrada y devuelve uno de los [[números enteros]] entre los que está comprendido como salida.

simbolizado, $f:\mathbb{R}\to \mathbb{Z} / f(x)=[x]$ o $f:\mathbb{R}\to \mathbb{Z} / f(x)=ent(x)$.

la **función parte entera por defecto** o **función suelo** toma un número real $x$ y devuelve el *menor* número entero de los dos entre los que $x$ está comprendido. si $x$ es entero, entonces devuelve el mismo número. 
- simbolizado como $f:\mathbb{R}\to\mathbb{Z}/f(x)=\left\lfloor x\right\rfloor$. 
- podemos decir que redondea hacia abajo los números reales a enteros.

la **función parte entera por exceso** o **función techo** es similar, pero asigna al número real $x$ el *mayor* de los dos enteros entre los que esté comprendido, y al mismo número si $x$ ya es entero. 
- simbolizado como $f:\mathbb{R}\to\mathbb{Z}/f(x)=\left\lceil x\right\rceil$. 
- podemos decir que redondea hacia arriba a los números reales a enteros.

la función parte entera no es [[función inyectiva|inyectiva]] pero si es [[función suryectiva|suryectiva]].

## por qué función parte entera?
como se implicó anteriormente, esta función hace lo que coloquialmente llamamos “redondear” números.