---
layout: post
title:  "Solución: Desafío matemático I"
tags:   Math
date:   2023-08-01 18:17:31
---

Para este primer desafío matemático te traigo 2 formas de llegar a la solución:

## Utilizando el método de sustitución

Este método sería el más clásico ya que basta con despejar la incógnita en la primera ecuación y reemplazarla en la segunda:

$$
\begin{align}
x - y &= 95\\
\sqrt{x}+\sqrt{y} &= 19
\end{align}
$$

$$
\begin{align}
x - y &= 95\\
x &= 95 + y
\end{align}
$$

$$
\begin{align}
\sqrt{x}+\sqrt{y} &= 19\\
\sqrt{95 + y}+\sqrt{y} &= 19\\
\sqrt{95 + y} &= 19 - \sqrt{y}\\
(\sqrt{95 + y})^2 &= (19 - \sqrt{y})^2\\
95 + y &= 361 - 38\sqrt{y} + y\\
38\sqrt{y} + y - y &= 361 - 95\\
38\sqrt{y} &= 266\\
\sqrt{y} &=  7\\
(\sqrt{y})^2 &= 7^2\\
y &= 49
\end{align}
$$

$$
\begin{align}
x &= 95 + 49\\
x &= 144
\end{align}
$$

## Utilizando productos notables

Este método es el más recomendado ya que de esta forma evitamos trabajar con ecuaciones con radicales. Para ello, tomaremos la primera ecuación y la expresaremos como una suma por diferencia, de esta forma podremos hacer uso de la segunda ecuación en la primera reemplazando ciertos términos:

$$
\begin{align}
x - y &= 95\\
\sqrt{x}+\sqrt{y} &= 19
\end{align}
$$

$$
\begin{align}
x - y &= 95\\
(\sqrt{x})^2 - (\sqrt{y})^2 &= 95\\
(\sqrt{x} + \sqrt{y})(\sqrt{x} - \sqrt{y}) &= 95\\
(19)(\sqrt{x} - \sqrt{y}) &= 95\\
\sqrt{x} - \sqrt{y} &= 5
\end{align}
$$

Efectuando una suma entre la ecuación que se acaba de generar y la segunda podremos encontrar fácilmente los valores de `x` e `y`:

$$
\begin{align}
\sqrt{x}+\sqrt{y} &= 19\\
\sqrt{x}-\sqrt{y} &= 5
\end{align}
$$

$$
\begin{align}
2\sqrt{x} &= 24\\
\sqrt{x} &= 12\\
(\sqrt{x})^2 &= 12^2\\
x &= 144
\end{align}
$$

$$
\begin{align}
\sqrt{144}+\sqrt{y} &= 19\\
12 + \sqrt{y} &= 19\\
\sqrt{y} &= 19 - 12\\
\sqrt{y} &= 7\\
(\sqrt{y})^2 &= 7^2\\
y &= 49
\end{align}
$$
