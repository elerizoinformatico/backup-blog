---
layout: post
title:  "Ecuación de segundo grado"
tags:   Math
date:   2023-09-07 12:19:06
---

Una ecuación es de **segundo grado** o **cuadrática** si el exponente de la incógnita es 2 (en otras palabras, $$x^2$$)

## Forma estándar

La forma estándar de una ecuación cuadrática es la siguiente:

$$
\begin{align}
ax^2 + bx + c &= 0
\end{align}
$$

Donde:
* `a`, `b` y `c` son valores conocidos (también llamados coeficientes)
* `a` no puede ser igual a `0` ($$a \neq 0$$)
* `x` es la incógnita (el valor que estamos buscando)

Ejemplos:

![Ejemplos ecuación cuadrática](/assets/img/EjemplosEcuacionCuadratica.png)

## Clasificación

Una ecuación cuadrática se puede clasificar en dos grupos:

### **Completa**

Los coeficientes `a`, `b` y `c` son distintos de `0`, es decir, la ecuación tiene la forma:

$$
\begin{align}
ax^2 + bx + c &= 0
\end{align}
$$

### **Incompleta**

Al menos uno de los coeficientes `b` y `c` es igual a `0`. En este grupo, encontraremos dos subgrupos:

**Pura:** El coeficiente `b` es igual a `0`, es decir, la ecuación tiene la forma:

$$
\begin{align}
ax^2 + c &= 0
\end{align}
$$

**Binomial:** El coeficiente `c` es igual a `0`, es decir, la ecuación tiene la forma:

$$
\begin{align}
ax^2 + bx &= 0
\end{align}
$$

## Resolución

Lo primero que debemos tener en cuenta es que en una ecuación cuadrática tendremos **2 soluciones**, las cuales pueden ser **distintas** o **iguales**.

A las soluciones de una ecuación de segundo grado se les conoce también como **raíces** o **ceros**.

### **Resolución de ecuaciones incompletas**

**Pura:** Para este tipo de ecuaciones, basta con despejar la incógnita ($$x^2$$) y aplicar raíz cuadrada para obtener las soluciones.

Ejemplo:

$$
\begin{align}
2x^2 - 72 &= 0\\
\end{align}
$$

Si despejamos `x` tenemos que:

$$
\begin{align}
\frac{2x^2}{2} - \frac{72}{2} &= 0\\
x^2 - 36 &= 0\\
x^2 &= 36
\end{align}
$$

Y aplicando raíz cuadrada nos queda:

$$
\begin{align}
\sqrt{x^2} &= \pm \sqrt{36}\\
x &= \pm 6
\end{align}
$$

Lo que significa que las **soluciones** o **raíces** de la ecuación son `6` y `-6`. Realicemos una comprobación:

$$
\begin{align}
2x^2 - 72 &= 0\\
2 \cdot (6^2) - 72 &= 0\\
72 - 72 &= 0\\
0 &= 0
\end{align}
$$

$$
\begin{align}
2x^2 - 72 &= 0\\
2 \cdot (-6)^2 - 72 &= 0\\
72 - 72 &= 0\\
0 &= 0
\end{align}
$$

Otra forma de resolver este tipo de ecuaciones es utilizar el producto notable **suma por su diferencia**:

$$
\begin{align}
\frac{2x^2}{2} - \frac{72}{2} &= 0\\
x^2 - 36 &= 0\\
x^2 - 6^2 &= 0\\
(x - 6)(x + 6) &= 0
\end{align}
$$

De esta forma, obtendremos dos ecuaciones lineales:

$$
\begin{align}
x - 6 &= 0\\
x &= 6
\end{align}
$$

$$
\begin{align}
x + 6 &= 0\\
x &= -6
\end{align}
$$

**Binomial:** Para este tipo de ecuaciones, debemos factorizar por `x` para que de esta forma la ecuación se convierta en un producto de dos términos lineales. En estas ecuaciones, una de sus soluciones siempre será igual a `0`.

Ejemplo:

$$
\begin{align}
x^2 - 3x &= 0\\
\end{align}
$$

Factorizando por `x` tenemos que:

$$
\begin{align}
x(x - 3) &= 0\\
\end{align}
$$

Y si separamos los términos líneales nos queda:

$$
\begin{align}
x &= 0
\end{align}
$$

$$
\begin{align}
x - 3 &= 0\\
x &= 3
\end{align}
$$

Por lo tanto, las soluciones o raíces para la ecuación serán `0` y `3`.

### **Resolución de ecuaciones completas**

Pendiente.
