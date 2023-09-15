---
layout: post
title:  "Ecuación de segundo grado II: Fórmula general, discriminante y tipos de soluciones"
tags:   Math
date:   2023-09-15 14:34:15
---

Continuando con este **mini-curso** sobre la **ecuación cuadrática** (si no has visto el capítulo anterior, te recomiendo hacer clic [aquí](https://elerizoinformatico.github.io/2023/09/07/ecuacion-de-segundo-grado-i/)), abarcaremos la fórmula general de resolución y los tipos de soluciones o raíces.

## Fórmula general

Las ecuaciones de segundo grado o cuadráticas (cualquiera sea su tipo) podemos resolverlas mediante la fórmula general:

$$
\begin{align}
x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\end{align}
$$

El símbolo $$\pm$$ nos indica que tendremos dos soluciones.

### **Demostración de la fórmula general**

Sea $$ax^2 + bx + c = 0$$ nuestra ecuación de segundo grado o cuadrática (cualquiera sea su tipo) procederemos a **"despejar"** la incógnita $$x$$:

$$
\begin{align}
ax^2 + bx + c &= 0
\end{align}
$$

Amplificamos por $$4a$$:

$$
\begin{align}
4a^2x^2 + 4abx + 4ac &= 0
\end{align}
$$

Sumamos $$b^2$$ en cada miembro de la igualdad:

$$
\begin{align}
4a^2x^2 + 4abx + 4ac + b^2 &= b^2
\end{align}
$$

Agrupamos términos de tal forma de obtener un **trinomio cuadrado perfecto**:

$$
\begin{align}
4a^2x^2 + 4abx + b^2 &= b^2 - 4ac
\end{align}
$$

Si $$(2ax + b)^2 = 4a^2x^2 + 4abx + b^2$$, entonces:

$$
\begin{align}
(2ax + b)^2 &= b^2 - 4ac
\end{align}
$$

Aplicamos raíz cuadrada en cada lado:

$$
\begin{align}
\sqrt{(2ax + b)^2} &= \pm \sqrt{b^2 - 4ac}\\
2ax + b &= \pm \sqrt{b^2 - 4ac}
\end{align}
$$

Por último, despejamos $$x$$:

$$
\begin{align}
x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\end{align}
$$
