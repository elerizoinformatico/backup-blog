---
layout: post
title:  "Ecuación de segundo grado III: Ecuaciones bicuadradas"
tags:   Math
date:   2023-11-28 09:15:37
---

En esta tercera parte del curso sobre la **ecuación cuadrática** (si no has visto el capítulo anterior, te recomiendo hacer clic [aquí](https://elerizoinformatico.github.io/2023/09/15/ecuacion-de-segundo-grado-ii/)), veremos un caso especial de la ecuación de cuarto grado: la **ecuación bicuadrada** o **bicuadrática**; la cual se puede resolver como una ecuación de segundo grado utilizando una sustitución o cambio de variable.

## Definición y forma estándar

Una ecuación **bicuadrada** o **bicuadrática** es una ecuación de cuarto grado donde los coeficientes que acompañan a los términos de grado impar son iguales a `0`:

$$
\begin{align}
ax^4 + 0x^3 + bx^2 + 0x + c &= 0
\end{align}
$$

Si eliminamos los términos iguales a `0` tendremos la forma estándar de una ecuación bicuadrada:

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

Por último, las soluciones de la ecuación serán las raíces de $$t_1$$ y $$t_2$$:

$$
\begin{align}
x_1 &= + \sqrt{t_1}\\
x_2 &= - \sqrt{t_1}\\
x_3 &= + \sqrt{t_2}\\
x_4 &= - \sqrt{t_2}\\
\end{align}
$$

### **Ejemplos**

### **1. $$x^4 - 2x^2 + 1 = 0$$.**

Como la ecuación ya se encuentra en su forma estándar, aplicamos el cambio de variable $$x^2 = t$$ y $$x^4 = t^2$$:

$$
\begin{align}
t^2 - 2t + 1 &= 0
\end{align}
$$

Tomamos los coeficientes $$a = 1$$, $$b = -2$$ y $$c = 1$$ y los reemplazamos en la fórmula general:

$$
\begin{align}
t &= \frac{-(-2) \pm \sqrt{(-2)^2 - 4\cdot(1)\cdot(1)}}{2\cdot(1)}\\
t &= \frac{2 \pm \sqrt{4 - 4}}{2}\\
t &= \frac{2 \pm \sqrt{0}}{2}\\
t &= \frac{2}{2}\\
t &= 1
\end{align}
$$

Para este caso, las raíces de `t` son reales e iguales ya que el discriminante es igual a `0`:

$$
\begin{align}
t_1 &= 1\\
t_2 &= 1
\end{align}
$$

Por último, deshacemos el cambio de variable para encontrar las soluciones de la ecuación original:

$$
\begin{align}
x_1 &= + \sqrt{t_1}\\
x_1 &= \sqrt{1}\\
x_1 &= 1
\end{align}
$$

$$
\begin{align}
x_2 &= - \sqrt{t_1}\\
x_2 &= - \sqrt{1}\\
x_2 &= -1
\end{align}
$$

$$
\begin{align}
x_3 &= + \sqrt{t_2}\\
x_3 &= + \sqrt{1}\\
x_3 &= 1\\
\end{align}
$$

$$
\begin{align}
x_4 &= - \sqrt{t_2}\\
x_4 &= - \sqrt{1}\\
x_4 &= -1
\end{align}
$$

Otra forma de resolver la ecuación es mediante la factorización:

$$
\begin{align}
x^4 - 2x^2 + 1 &= 0\\
(x^2 - 1)^2 &= 0\\
(x^2 - 1)(x^2 - 1) &= 0\\
(x - 1)(x + 1)(x - 1)(x + 1) &= 0
\end{align}
$$

Donde tenemos que las raíces son $$x_1 = 1$$, $$x_2 = -1$$, $$x_3 = 1$$ y $$x_4 = -1$$.

### **2. $$x^4 - 10x^2 + 9 = 0$$.**

Aplicamos cambio de variable:

$$
\begin{align}
t^2 - 10t + 9 &= 0
\end{align}
$$

Tomamos los coeficientes $$a = 1$$, $$b = -10$$ y $$c = 9$$ y los reemplazamos en la fórmula general:

$$
\begin{align}
t &= \frac{-(-10) \pm \sqrt{(-10)^2 - 4\cdot(1)\cdot(9)}}{2\cdot(1)}\\
t &= \frac{10 \pm \sqrt{100 - 36}}{2}\\
t &= \frac{10 \pm \sqrt{64}}{2}\\
t &= \frac{10 \pm 8}{2}\\
\end{align}
$$

Para este caso, las raíces de `t` son reales y distintas ya que el discriminante es mayor que `0`:

$$
\begin{align}
t_1 &= \frac{10 + 8}{2}\\
t_1 &= \frac{18}{2}\\
t_1 &= 9
\end{align}
$$

$$
\begin{align}
t_2 &= \frac{10 - 8}{2}\\
t_2 &= \frac{2}{2}\\
t_2 &= 1
\end{align}
$$

Por último, deshacemos el cambio de variable para encontrar las soluciones:

$$
\begin{align}
x_1 &= + \sqrt{t_1}\\
x_1 &= \sqrt{9}\\
x_1 &= 3
\end{align}
$$

$$
\begin{align}
x_2 &= - \sqrt{t_1}\\
x_2 &= - \sqrt{9}\\
x_2 &= -3
\end{align}
$$

$$
\begin{align}
x_3 &= + \sqrt{t_2}\\
x_3 &= + \sqrt{1}\\
x_3 &= 1\\
\end{align}
$$

$$
\begin{align}
x_4 &= - \sqrt{t_2}\\
x_4 &= - \sqrt{1}\\
x_4 &= -1
\end{align}
$$

Esta ecuación, al igual que la anterior, también se puede resolver mediante factorización:

$$
\begin{align}
x^4 - 10x^2 + 9 &= 0\\
(x^2 - 9)(x^2 - 1) &= 0\\
(x - 3)(x + 3)(x - 1)(x + 1) &= 0\\
\end{align}
$$

Donde tenemos las raíces $$x_1 = 3$$, $$x_2 = -3$$, $$x_3 = 1$$ y $$x_4 = -1$$.

### **3. $$x^4 - 16x^2 - 225 = 0$$.**

Aplicamos cambio de variable y reemplazamos los coeficientes en la fórmula general:

$$
\begin{align}
t^2 - 16t - 225 &= 0
\end{align}
$$

$$
\begin{align}
t &= \frac{-(-16) \pm \sqrt{(-16)^2 - 4\cdot(1)\cdot(-225)}}{2\cdot(1)}\\
t &= \frac{16 \pm \sqrt{256 + 900}}{2}\\
t &= \frac{16 \pm \sqrt{1156}}{2}\\
t &= \frac{16 \pm 34}{2}\\
\end{align}
$$

Las raíces de `t` son reales y distintas ya que el discriminante es mayor que `0`:

$$
\begin{align}
t_1 &= \frac{16 + 34}{2}\\
t_1 &= \frac{50}{2}\\
t_1 &= 25
\end{align}
$$

$$
\begin{align}
t_2 &= \frac{16 - 34}{2}\\
t_2 &= \frac{-18}{2}\\
t_2 &= -9
\end{align}
$$

Deshacemos el cambio de variable para encontrar las soluciones:

$$
\begin{align}
x_1 &= + \sqrt{t_1}\\
x_1 &= \sqrt{25}\\
x_1 &= 5
\end{align}
$$

$$
\begin{align}
x_2 &= - \sqrt{t_1}\\
x_2 &= - \sqrt{25}\\
x_2 &= -5
\end{align}
$$

$$
\begin{align}
x_3 &= + \sqrt{t_2}\\
x_3 &= \sqrt{-9}
\end{align}
$$

$$
\begin{align}
x_4 &= - \sqrt{t_2}\\
x_4 &= - \sqrt{-9}
\end{align}
$$

En este caso, la ecuación bicuadrada tiene solo 2 soluciones reales ya que las otras son complejas conjugadas.

## Ejercicios aplicados

1. $$x^4 = x^2$$.
2. $$x^4 - 13x^2 + 36 = 0$$.
3. $$x^4 - 74x^2 + 1225 = 0$$.
4. $$x^4 - -5x^2 + 6 = 0$$.
5. $$x^4 - 9x^2 = 0$$.
6. $$x^4 + 2x^2 = 0$$.
7. $$x^4 - 80x^2 - 81 = 0$$.
8. Encontrar una ecuación bicuadrada que tenga al menos la solución $$x = \sqrt{2 + \sqrt{3}}$$.
9. $$x^6 - 19x^3 - 216 = 0$$.
10. $$x^6 - 7x^3 - 8 = 0$$.

Si tienes dudas con los contenidos vistos en este apartado o con los ejercicios aplicados, no dudes en escribirme en la caja de comentarios.

<script src="https://utteranc.es/client.js"
        repo="elerizoinformatico/elerizoinformatico.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>
