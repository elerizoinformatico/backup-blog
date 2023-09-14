---
layout: post
title:  "Ecuación de segundo grado I: Definición, clasificación y métodos de resolución"
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

Otra forma de resolver este tipo de ecuaciones es utilizando el producto notable **suma por su diferencia**:

$$
\begin{align}
a^2 - b^2 &= (a + b)(a - b)
\end{align}
$$

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

Por lo tanto, las soluciones o raíces para la ecuación son `0` y `3`.

### **Resolución de ecuaciones completas**

Para este tipo de ecuaciones podemos **factorizar** o bien, utilizar la **fórmula general** de resolución (la cual veremos más adelante en detalle).

Ejemplo:

$$
\begin{align}
x^2 - 5x + 6 &= 0
\end{align}
$$

Para resolverla mediante la **factorización** debemos recordar el **producto de dos binomios con término común**:

$$
\begin{align}
x^2 + (a + b)x + ab &= (x + a)(x + b)
\end{align}
$$

Con esto aclarado, debemos encontrar entonces dos números que al multiplicarlos nos de `6` y que al sumarlos nos de `-5`.

Posibles opciones:
* **$$6$$ y $$1$$**: $$6 \cdot 1 = 6$$ y $$6 + 1 = 7$$. Por lo tanto, $$6$$ y $$1$$ no son los números que buscamos.
* **$$2$$ y $$3$$**: $$2 \cdot 3 = 6$$ y $$2 + 3 = 5$$. Por lo tanto, $$2$$ y $$3$$ no son los números que buscamos.
* **$$2$$ y $$-3$$**: $$2 \cdot (-3) = -6$$ y $$2 + (-3) = -1$$. Por lo tanto, $$2$$ y $$-3$$ no son los números que buscamos.
* **$$-2$$ y $$-3$$**: $$(-2) \cdot (-3) = 6$$ y $$(-2) + (-3) = -5$$. Por lo tanto, $$-2$$ y $$-3$$ **si** son los números que buscamos.

Por lo tanto, la ecuación $$x^2 - 5x + 6 = 0$$ podemos escribirla como:

$$
\begin{align}
x^2 + (-2 + -3)x + ((-2) \cdot (-3)) &= 0\\
(x - 2)(x - 3) &= 0
\end{align}
$$

En donde tenemos que:

$$
\begin{align}
x - 2 &= 0\\
x &= 2
\end{align}
$$

$$
\begin{align}
x - 3 &= 0\\
x &= 3
\end{align}
$$

Finalmente, las raíces de la ecuación son `2` y `3`.

## Ejercicios aplicados

1. $$x^2 - 9x = 0$$.
2. $$(x + 5)^2 = 25$$.
3. $$3x^2 -48 = 0$$.
4. $$x + 3x^2 = 4x$$.
5. $$3x^2 + 7x -22 = 5 + 7x$$.
6. $$x^2 = 2 + x$$.
7. $$x^2 - 2x + 1 = 0$$.
8. $$x^2 - 2x = 15$$.
9. $$x^2 - 7x + 10 = 0$$.
10. $$6x + x(x - 13) = 18$$.
11. $$x^2 + x - 6 = 0$$.
12. $$x^2 - 4x + 4 = 0$$.
13. $$2x - 3 = 1 - 2x + x^2$$.
14. $$x^2 + (7 - x)^2 = 25$$.
15. $$x^2 - (x + 1)^2 = 2 - x^2$$.
16. $$-x^2 = 6x + 8$$.

<script src="https://utteranc.es/client.js"
        repo="elerizoinformatico/elerizoinformatico.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>
