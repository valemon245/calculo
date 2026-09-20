---
Created: 2024-04-02
---
# composición de funciones
#lógica #funciones 

>[!abstract] definición
>teniendo tres [[conjunto|conjuntos]] $A,B,C$ y dos [[función|funciones]] $f: A\to B$ y $g: B\to C$, $g\circ f$ es una función de $A\to C$.

un concepto similar a la [[composición de relaciones]].

si la [[imagen de la relación|imagen]] de $f$ es igual o está incluída en el [[dominio de la relación|dominio]] de $g$, podemos asignar una imagen a la imagen de $f$, que llamamos $g[f(x)]$.  
- simbólicamente, $g\circ f:A\to C/(g\circ f)(x)=g[f(x)]$.

probemos porqué tiene sentido usando $f:A\to B$ y $g:C\to D$:
- podemos afirmar que $\forall x \in A,f(x)\in B$.
- si $B\subseteq C$, se puede afirmar que $\forall x\in A, f(x)\in C$. 
- ya que $f(x)\in C$, que es el dominio de $g$, podemos aplicar $g$ a $f(x)$, lo que nos deja con $g[f(x)]=(g\circ f)(x)$.

ahora un ejemplo más concreto. digamos que tenemos $f:\mathbb{R}\to \mathbb{R} / f(x)=x+1$ y $g:\mathbb{R} \to \mathbb{R} / g(x)=x^{2}$. 

vemos que $Im(f)=\mathbb{R}$ y $Dm(g)=\mathbb{R}$. $\mathbb{R} \subset \mathbb{R}$, por lo tanto $g\circ f$ sí es una función y se puede definir como $g\circ f:\mathbb{R}\to \mathbb{R}/(g\circ f)(x)=g[\:x+1]=\left(x+1\right)^{2}$.

![[Captura de pantalla 2024-04-02 171703.png]]

para un contra-ejemplo, analicemos $f:\mathbb{R}\to \mathbb{R}/f(x)=x^{2}$ y $g:\mathbb{R}^{+}\to \mathbb{R}/g(x)=\sqrt{x}$:
- la imagen de $f$ son todos los nros. reales no negativos, es decir $[0,\infty)$.
- el dominio de $g$ es $\mathbb{R}^{+}$, todos los nros. reales positivos.

$g\circ f$ *no* es una función bien definida porque el 0 no forma parte de $Dm(g)$, por lo tanto $g[f(x)]$ donde $x=0$ no tiene sentido.
