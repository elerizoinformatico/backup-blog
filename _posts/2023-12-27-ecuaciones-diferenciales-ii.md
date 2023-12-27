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

Supondremos que la solución $$f$$ es una función con valores reales, es decir, $$I \in \mathbb{R}$$.

El intervalo de solución $$I$$ también es conocido como:
* Intervalo de definición
* Intervalo de existencia
* Intervalo de validez
* Dominio de una función

Y puede ser abierto $$(a,b)$$, cerrado $$[a,b]$$, infinito $$(a,+\infty)$$, etc.

## Verificación de una Solución

Para verificar que una función dada es solución de una ecuación diferencial, debemos realizar una sustitución en la ecuación y corroborar que en cada lado se produzca una igualdad para toda $$x$$ en el intervalo.

Ejemplo:

Para la ecuación diferencial ordinaria a continuación verificaremos que la función $$y$$ es una solución:

$$
\begin{align}
\frac{dy}{dx} &= x\sqrt{y}
\end{align}
$$

$$
\begin{align}
y &= \frac{x^4}{16}
\end{align}
$$

Lo primero que debemos hacer es derivar la función ya que en la ecuación tenemos una derivada de primer orden:

$$
\begin{align}
\frac{dy}{dx} &= \frac{x^3}{4}
\end{align}
$$

Luego, reemplazamos los valores $$y$$ e $$y'$$:

$$
\begin{align}
\frac{x^3}{4} &= x\sqrt{\frac{x^4}{16}}\\
\frac{x^3}{4} &= x\frac{x^2}{4}\\
\frac{x^3}{4} &= \frac{x^3}{4}\\
\end{align}
$$

Por lo tanto, podemos afirmar que la función $$y$$ es una solución de la ecuación diferencial.

## Solución trivial

Si la función $f(x) = 0$$$ es una solución de una ecuación diferencial en un intervalo $$I$$, decimos que $$f$$ es una **solución trivial**.

Tomando el ejemplo anterior tenemos:

$$
\begin{align}
\frac{dy}{dx} &= x\sqrt{y}
\end{align}
$$

$$
\begin{align}
y &= 0
\end{align}
$$

Derivamos la función:

$$
\begin{align}
y' &= 0
\end{align}
$$

Por último, reemplazamos los valores:

$$
\begin{align}
0 &= x\sqrt{0}\\
0 &= 0
\end{align}
$$

Por lo tanto, la función $$f(x) = 0$$ también es una solución de la ecuación diferencial.

## Ejercicios aplicados

Hola.
