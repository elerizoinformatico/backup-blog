---
layout: post
title:  "Ecuaciones diferenciales II: Verificación de soluciones"
tags:   Math
date:   2023-12-27 13:15:37
---

En este segundo capítulo del curso sobre **ecuaciones diferenciales** (si no has visto el capítulo anterior, te recomiendo hacer clic [aquí](https://elerizoinformatico.github.io/2023/12/26/ecuaciones-diferenciales-i/)), estudiaremos la solución o función solución de una ecuación para así entender su comportamiento y propiedades.

Tener en cuenta que a lo largo de este curso trabajaremos con las **ecuaciones diferenciales ordinarias** (EDO).

## Solución de una EDO

Una **solución de una ecuación diferencial** es una **función** $$f$$ definida en un intervalo $$I$$, que tiene al menos $$n$$ derivadas continuas en $$I$$ y que al sustituirlas en la ecuación diferencial ordinaria de n-ésimo orden, reducen la ecuación a una identidad.

Supondremos que la solución $$f$$ es una función con valores reales, es decir, $$f \in \mathbb{R}$$.

El intervalo de solución $$I$$ también es conocido como:
* Intervalo de definición
* Intervalo de existencia
* Intervalo de validez
* Dominio de una función

Y puede ser abierto $$(a,b)$$, cerrado $$[a,b]$$, infinito $$(a,+\infty)$$, etc.

## Verificación de una Solución

Para verificar que una función dada es solución de una ecuación diferencial, debemos realizar una sustitución en la ecuación y corroborar que en cada lado se produzca una igualdad para toda $$x$$ en el intervalo.

Ejemplo:

Para la ecuación diferencial a continuación:

$$
\begin{align}
\frac{dy}{dx} &= x\sqrt{y}
\end{align}
$$

Verificaremos que la función:

$$
\begin{align}
y &= \frac{x^4}{16}
\end{align}
$$

Es solución.
