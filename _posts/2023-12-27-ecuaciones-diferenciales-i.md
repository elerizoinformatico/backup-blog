---
layout: post
title:  "Ecuaciones diferenciales I: Definición y clasificación"
tags:   Math
date:   2023-12-27 09:27:11
---

Las ecuaciones diferenciales son **ecuaciones que contienen derivadas** de una o más variables dependientes con respecto a una o más variables independientes.

## Clasificación

Se pueden clasificar de acuerdo a su:
* Tipo
* Orden
* Linealidad
* Homogeneidad


### **Clasificación por tipo**

**Ordinarias** (EDO): Son ecuaciones cuyas derivadas siempre son con respecto a una misma variable.

$$
\begin{align}
4\frac{dy}{dx} + 20y &= 5e^x
\end{align}
$$

$$
\begin{align}
y''' - 6y'' + 12y' - 8y &= 0
\end{align}
$$

**En derivadas parciales** (EDP): Son ecuaciones cuya variable dependiente se deriva con respecto a dos o más variables independientes.

$$
\begin{align}
\frac{d^2f}{dx^2} + \frac{d^2f}{dy^2} &= 0
\end{align}
$$

$$
\begin{align}
u_{xx} + u_{yy} &= xy
\end{align}
$$

### **Clasificación por orden**

**Primer orden**: Si en la ecuación la mayor derivada es de primer orden.

$$
\begin{align}
4\frac{dy}{dx} + 20y &= 5e^x
\end{align}
$$

$$
\begin{align}
\left({dP\over dt}\right)^2 + 4P &= t(t-1)
\end{align}
$$

**Orden superior**: Si en la ecuación la mayor derivada es de segundo orden o superior.

$$
\begin{align}
y''' - 6y'' + 12y' - 8y &= 0
\end{align}
$$

$$
\begin{align}
\frac{d^2f}{dx^2} + \frac{d^2f}{dy^2} &= 0
\end{align}
$$

### **Clasificación por linealidad**

Existen 2 condiciones que determinarán si una ecuación diferencial es lineal:
1. La variable dependiente y todas sus derivadas son de primer grado, es decir, la potencia de todos los términos es 1.
2. Los coeficientes de los términos de la variable dependiente son constantes o dependen de la variable independiente.

**Lineal**: Si la ecuación cumple las 2 condiciones de linealidad.

$$
\begin{align}
4\frac{dy}{dx} + 20y &= 5e^x
\end{align}
$$

$$
\begin{align}
y''' - 6y'' + 12y' - 8y &= 0
\end{align}
$$

**No lineal**: Si la ecuación no cumple las 2 condiciones de linealidad, es decir, solo cumple una o ninguna de ellas.

$$
\begin{align}
\left({dP\over dt}\right)^2 + 4P &= t(t-1)
\end{align}
$$

$$
\begin{align}
\cos(y) \frac{dy}{dt} + 4t^2 &= 0
\end{align}
$$

Hola.

$$
\begin{align}
L\frac{d^2q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q &= E(t)
\end{align}
$$
