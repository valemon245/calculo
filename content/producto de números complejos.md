---
Created: 2024-06-21
---
# producto de complejos
#números 

>[!abstract] definición
>reglas y propiedades para la operación de producto en los [[números complejos]].

tenemos $z=(a,b)$ y $w=(c,d)$. el producto de dos números complejos se define como:
$$\large z\cdot w=(a,b)\cdot(c,d)=(ac-bd,ad+bc)$$

## propiedades
se verifican los siguientes axiomas:
- ley de cierre: $\forall z_1,z_2\in \mathbb{C}:z_1\cdot z_2\in \mathbb{C}$
- propiedad asociativa: $\forall z_1,z_2,z_3\in \mathbb{C}:(z_1\cdot z_2)\cdot z_3=z_1\cdot (z_2\cdot z_3)$
- propiedad conmutativa: $\forall z_1,z_2\in C:z_1\cdot z_2=z_2\cdot z_1$
- existencia de elemento neutro: $\exists z_1=(1,0)\in \mathbb{C}/\forall z=(a,b)\in \mathbb{C}:z_1\cdot z=z$
- existencia de elemento simétrico (inverso): $\forall z\in \mathbb{C},z\neq 0,\exists z^{-1}\in \mathbb{C}/z\cdot z^{-1}=(1,0)$

el inverso de $z$ se define como:
$$\text{si }z=(a,b)\Rightarrow z^{-1}=\left(\frac a{a^2+b^2},\frac{-b}{a^2+b^2}\right)/z\cdot z^{-1}=(1,0)$$

las mismas propiedades se verifican en la [[suma de números complejos]].