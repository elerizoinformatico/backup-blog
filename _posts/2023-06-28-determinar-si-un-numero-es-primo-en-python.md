---
layout: post
title:  "Determinar si un número es primo en Python"
tags:   Computing
date:   2023-06-28 16:12:35
---

Antes de continuar, debes tener claro lo que es un número primo: **son aquellos que sólo son divisibles por uno y por sí mismos**. Se entiende por divisible a que el resultado sea un número entero, es decir, no decimal.

Por lo tanto, números como el **2**, **3**, **5**, **7** y **11** son primos ya que no hay ningún número que los pueda dividir de manera entera (excluyendo al 1 y al propio número). Sin embargo, el número **10** no es primo ya que se puede dividir por 2 y por 5.

Los números primos son un concepto un tanto enigmático y muy estudiado. Algunas teorías como la **Conjetura de Goldbach** son de lo más interesantes.

***Todo número entero mayor que 5 se puede escribir como suma de tres números primos.***

Veamos ahora cómo se puede implementar en Python un algoritmo que determine si un número ingresado por teclado es primo o no.

## Desarrollando el algoritmo

En el apartado anterior te pudiste dar cuenta que un número primo sólo tiene **2** divisores, por lo que podemos realizar una iteración que recorra todos los números, desde el 1 hasta el número ingresado, y contar a los que son divisores mediante el operador módulo (`%`). Si al terminar el ciclo la cantidad de dividores es 2, entonces el número ingresado es primo y, en caso contrario, no lo será.

```python
n = int(input("Ingrese un numero: "))
# Leemos un numero por teclado y lo transformamos a entero

c = 0
i = 1
# Definimos 2 variables:
# c sera un contador de divisores
# i sera una auxiliar que recorrera el ciclo iterativo

while i <= n:
    if n % i == 0:
        c = c + 1
        # Incrementamos en 1 el contador c si la auxiliar i es divisor de n
    i = i + 1
    # Incrementamos en 1 la auxiliar i para evitar un ciclo infinito (loop)

if c == 2:
    print("El numero ingresado es primo")
    # Si el contador es igual a 2, entonces el numero es primo
else:
    print("El numero ingresado NO es primo")
    # En caso contrario, el numero no sera primo
```

También podemos utilizar un ciclo `for` que es exactamente lo mismo:

```python
n = int(input("Ingrese un numero: "))

c = 0

for i in range(1,n+1):
    if n % i == 0:
        c = c + 1

# Para el ciclo for consideramos el rango (1,n+1) ya que por defecto es (0,n-1)

if c == 2:
    print("El numero ingresado es primo")
else:
    print("El numero ingresado NO es primo")
```

## Otras formas de resolver la misma interrogante

Otra forma de determinar si un número es primo o no es mediante un ciclo que recorra el rango `(2,n-1)` y busque divisores exactos. En caso de existir uno, se entiende que el número **no** es primo y, en caso contrario, lo será.

```python
def es_primo(n):
    for i in range(2,n):
        if n % i == 0:
            return False
            # Apenas encontramos un divisor, retornamos False (no es primo)
    return True
    # En caso de no encontrar ningun divisor, retornamos True (es primo)

n = int(input("Ingrese un numero: "))

es_primo(n)
```

Por último, podemos utilizar la recursividad basándonos en la solución anterior:

```python
def primo_recursivo(n,i=2):
    if i >= n:
        return True
        # Si i >= n se cumple significa que ya hemos dividido el número
        # ingresado con todos los anteriores y por lo mismo, es primo
    elif n % i != 0:
        return primo_recursivo(n,i+1)
        # Si i no es divisor, continuamos llamando a la función (con i+1)
    else:
        return False
        # Si detectamos un divisor exacto, rentonces no es primo

n = int(input("Ingrese un numero: "))

primo_recursivo(n)
```

Espero que hayas aprendido todas las formas de determinar si un número es primo o no que aquí te muestro. Si tienes problemas con los operadores y funciones aquí utilizadas, te recomiendo visitar el tutorial oficial de python haciendo clic [aquí](https://docs.python.org/es/3/tutorial/).

<script src="https://utteranc.es/client.js"
        repo="elerizoinformatico/elerizoinformatico.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>
