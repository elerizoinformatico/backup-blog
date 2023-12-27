---
layout: post
title:  "Ecuaciones diferenciales I: Definición y clasificación"
tags:   Math
date:   2023-12-26 09:27:11
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

**Parciales** (EDP): Son ecuaciones cuya variable dependiente se deriva con respecto a dos o más variables independientes.

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

Para el segundo ejemplo, tener en cuenta que la ecuación sigue siendo de primer orden por la diferencial y no por el cuadrado:

$$
\begin{align}
\frac{d^2y}{dx^2} \neq \left({dy\over dx}\right)^2
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

En el primer ejemplo no se cumple la condición 1 pero sí la 2 y en el segundo ocurre lo contrario (se cumple la condición 1 pero no la 2).

### **Clasificación por homogeneidad**

**Homogénea**s: Si en cada uno de los términos de la ecuación se encuentra presente la variable dependiente en cualquier forma o como cualquier derivada de la variable independiente.

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

**No homogéneas**: Si existe al menos un término de la ecuación en donde no se encuentre presente la variable dependiente en cualquier forma o como cualquier derivada de la variable independiente.

$$
\begin{align}
4\frac{dy}{dx} + 20y &= 5e^x
\end{align}
$$

$$
\begin{align}
L\frac{d^2q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q &= E(t)
\end{align}
$$

## Notación para las derivadas

Existen dos tipos de notaciones para las derivadas:

**Notación de Leibniz**:

$$
\begin{align}
\frac{dy}{dx}, \frac{d^2y}{dx^2}, \frac{d^3y}{dx^3}, ..., \frac{d^ny}{dx^n}
\end{align}
$$

**Notación prima**:

$$
\begin{align}
y', y'', y''', y^{(4)}, y^{(5)}, ..., y^{(n)}
\end{align}
$$

La notación de Leibniz tiene una ventaja sobre la notación prima y es que muestra claramente las variables dependientes e independientes. Por lo mismo, es más común encontrar las ecuaciones diferenciales escritas con la primera notación.

## Ejercicios aplicados

Clasifica las siguientes ecuaciones diferenciales de acuerdo a su tipo, orden, linealidad y homogeneidad:

* $$4\frac{dy}{dx} + 20y = 5e^x$$.
* $$y''' - 6y'' + 12y' - 8y = 0$$.
* $$\frac{d^2f}{dx^2} + \frac{d^2f}{dy^2} = 0$$.
* $$L\frac{d^2q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q = E(t)$$.
* $$\left({dP\over dt}\right)^2 + 4P = t(t-1)$$.
* $$\cos(y) \frac{dy}{dt} + 4t^2 = 0$$.
* $$(1-x)y'' -4xy'+5y = \cos(x)$$.
* $$x\frac{d^3y}{dx^3} - \left({dy\over dx}\right)^4 + y = 0$$.
* $$t^5y^{(4)} - t^3y'' + 6y = 0$$.
* $$\frac{d^2R}{dt^2} = - \frac{k}{R^2}$$.

Si tienes dudas con los contenidos vistos en este apartado o con los ejercicios aplicados, no dudes en escribirme en la caja de comentarios.

<script src="https://utteranc.es/client.js"
        repo="elerizoinformatico/elerizoinformatico.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>
