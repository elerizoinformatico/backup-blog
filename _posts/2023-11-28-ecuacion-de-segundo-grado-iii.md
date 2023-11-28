---
layout: post
title:  "Ecuación de segundo grado III: Ecuaciones bicuadradas"
tags:   Math
date:   2023-11-28 09:15:37
---

En esta tercera parte del curso sobre la **ecuación cuadrática** (si no has visto el capítulo anterior, te recomiendo hacer clic [aquí](https://elerizoinformatico.github.io/2023/09/15/ecuacion-de-segundo-grado-ii/)), veremos un caso especial de la ecuación de cuarto grado: la **ecuación bicuadrada** o bicuadrática; la cual se puede resolver como una ecuación de segundo grado utilizando una sustitución o cambio de variable.

## Definición y forma estándar

Una ecuación **bicuadrada** o **bicuadrática** es una ecuación de cuarto grado donde los coeficientes que acompañan a los términos de grado impar son iguales a `0`.

$$
\begin{align}
ax^4 + 0x^3 + bx^2 + 0x + c &= 0
\end{align}
$$

Eliminando los términos iguales a `0` tenemos la forma estándar de una ecuación bicuadrada:

$$
\begin{align}
ax^4 + bx^2 + c &= 0
\end{align}
$$

Como se trata de una ecuación de cuarto grado tendremos **4 raíces**, las cuales pueden ser todas reales, todas complejas o combinadas (2 reales y 2 complejas).

## Resolución

Para resolver una ecuación bicuadrada debemos efectuar el siguiente cambio de variable:

$$
\begin{align}
x^2 &= t\\
x^4 &= t^2
\end{align}
$$

Con este cambio, la ecuación se convertirá en una de segundo grado que ya sabemos como resolver:

$$
\begin{align}
at^2 + bt + c &= 0
\end{align}
$$

Por último, las cuatro soluciones de la ecuación serán las raíces de $$t_1$$ y $$t_2$$:

$$
\begin{align}
x_1 &= + \sqrt{t_1}\\
x_2 &= - \sqrt{t_1}\\
x_3 &= + \sqrt{t_2}\\
x_4 &= - \sqrt{t_2}\\
\end{align}
$$
