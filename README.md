# Ejercicios programación

Estos ejercicios sirven principalmente para cuando estás comenzando a aprender a programar.

Ya has aprendido los tipos de datos básicos, ya sabes lo que es una lista o array, un variable, un texto, un booleano...

Estos ejercicios te ayudarán a coger solutra a la hora de tratar con ellos.

# STRINGS O TEXTO

## Invierte el texto

```
Programa una función a la cual, cuando se le pase un texto, lo devuelva invertido:

Ejemplo

mi_funcion('hola que tal')

Dará como resultado 'lat euq aloh'
```

## Palíndromos

```
Programa una función que nos devuelva si una palabra o texto es palíndromo (TRUE) o no (FALSE). 

Una palabra o texto es palíndromo si se lee igual de izquierda a derecha que de derecha a izquierda.

Ejemplo

mi_funcion('dabale arroz a la zorra el abad')

Dará como resultado true, ya que es palíndroma
```

## Cuenta el número de veces que se repite una palabra en un texto largo

```
Programa una función a la cual se le pasen dos paremetros, que serán un texto largo y una palabra a comprobar
la función retornará cuantas veces se repite la palabra solicitada.

Ejemplo:

texto = "Hola, en un lugar de la mancha Hola, vivía Hola"

mi_funcion("Hola", texto)

Dará como resultado 3
```

## Elimina una palabra del texto

```
Program una función que dada una palabra y un texto, elimine esa palabra del texto y lo devuelva.

Ejemplo:

texto = "Es mejor ser explícito que hacerse entender de otras formas"

mi_funcion("hacerse", texto)

Dará como resultado "Es mejor ser explícito que entender de otras formas"
```

## Contabiliza el número de caracteres en un string

```
Programa una función la cual te brinde el número de caracteres en un string:

Ejemplo

mi_funcion('hola que tal')

Dará como resultado 12
```

## Obten cierto número de caracteres de un texto

```
Programa una función la cual te devuelva el texto recortado según el número de caracteres definidos:

Ejemplo

mi_funcion('hola que tal', 10)

Dará como resultado 'hola que t'
```

## Crea un array derivado de un separador

```
Programa una función la cual te devuelva un array de texto separados por cierto caracter:

Ejemplo

mi_funcion('hola que tal', ' ')

Dará como resultado ['hola','que','tal']
```

## Repetir un texto X veces

```
Programa una función que reciba dos parámetros, un texto y un número, y que pinte en consola (o similar) dicho texto, la cantidad de veces que indique el número:

Ejemplo

mi_funcion('Hell Yeah', 3)

Dará como resultado

Hell Yeah
Hell Yeah
Hell Yeah

```

# NUMEROS

## Suma dos números

```
Programa una función que reciba dos parametros (2 números) y devuelva la suma.

Ejemplo

mi_funcion(1,2)

Dará como resultado 3
```

## Número al cuadrado

```
Programa una función que reciba un número y retorne ese mismo número elevado al cuadrado:

Ejemplo

mi_funcion(3)

Dará como resultado 9
```

## Números primos

```
Programa una función que reciba un número y devuelva si es primo (TRUE) o no (FALSE).
** Número primo **: es aquel que sólo es divisible por uno y por si mismo.

Ejemplo:

mi_funcion(7)

Dará como resultado TRUE
```

## Número capicúas

```
Programa una función que reciba un número y devuelve si es capicúa (TRUE) o no (FALSE).

Ejemplo:

mi_funcion(12321)
Dará como resultado TRUE.

mi_funcion(5252)
Dará como resultado FALSE.
```

## Cambio de base decimal a binaria

```
Programa una función a la cual se le pasa un numero decimal (en base 10) y te devuelva su representación binaria

mi_funcion(5) = 101
mi_funcion(7) = 111
```

## Cambio de base binaria a decimal
```
Programa una función a la cual se le pasa un número en binario (base 2) y devuelva su representación decimal
mi_funcion(100) = 4
mi_funcion(110) = 6
``` 

## Cambio de base decimal a octal

```
Programa una función a la cual se le pasa un numero decimal (en base 10) y te devuelva su representación en octal (base 8)

mi_funcion(5) = 5
mi_funcion(8) = 10
mi_funcion(10) = 12
```

## Cambio de base octal a decimal

```
Programa una función a la cual se le pasa un número en octal (base 8) y devuelva su representación decimal

mi_funcion(13) = 11
mi_funcion(20) = 16
``` 

## Aplicar el descuento a un número

```
Programa una función la cual te genere el monto final aplicandole un descuento (regla de tres), donde le pases el primer parámetro que sería el descuento o porcentaje a aplicar y el segundo parámetro es la cantidad a la cual le quieres aplicar el descuento
mi_funcion(20, 1000) 

El resultado debe ser 800

ejemplo: https://jsfiddle.net/Alan_van_Buuren/mL0dnj83/3/
``` 

# Arrays

## Imprime uno a uno los elementos de un array dado

```
Programa una función que reciba como parametro un array, y que imprima por consola uno a uno sus elementos, diciendo su indice:

mi_funcion(['hola', 1, True])

El resultado deber ser:

-  hola ocupa el indice 0 en el array
-  1 ocupa el indice 1 en el array
- True ocupa el indice 2 en el array
```

## Dado un array numérico devuelve otro array con los numéros elevados al cuadrado

```
mi_funcion([1,4,5])

El resultado debe ser [1, 16, 25]
```

