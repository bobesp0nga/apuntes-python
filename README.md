# apuntes-python

mis apuntes de pyhton

## Print

La funicón `print()` se encarga de imprimir por pantalla

Por ejemplo: 

```python
print("Hola que tal")
```

Podemos concatenar cadenas de caracteres
```python
print("hola, que tal")
print("hola" + "Ivan")
```

## Input
La funicón `input()` nos permite introducir información a través del teclado.
Podemos utilizarlo sin indicar nada entre parentesis:

```python
print("introduce tu nombre")
input()
```
Si escribimos dentro de los parentesis, podemos mostrar información antes de escribir:
```python
input("Introduce tu nomre")
```

## Variables
Las variables nos permiten guardar en ellas información. Hay muchos tipos de variables: 

- **Enteros**: 5
- **Cadenas de texto**: Ivan
- **Booleanos**: True, False

Las variables tienen un nombre que las identifica. Por ejemplo:

```python
Edad = 20
Nombre = Ivan
vivo = True
```
Para imprimir uan variable indicamos su nombre sin comillas:
```pyhton
nombre = "Ivan"
print(nombre)
```
El signo igual asigna un valor a la variable.

Un ejemplo completo:

```python
nombre = input("dime tu nombre")
print(nombre)
```
Si queremos convertir el resultado de un input en un número utilizamos la funicón `int()`. Por ejemplo:

```python
edad = int(input("dime tu edad"))
print(edad+5)
```

## Condicionales
Para decicdir ejecutar o no un bloque de código en funciión de si se cumple o no una condición utilizamos `if`.
```python
edad = 18
if edad>=18:
    print("mayor de edad")
```
Tamién podemos usar `else`para cuando la conidicón no se cumpla.
```python
edad = 18
if edad>=18:
    print("mayor de edad")
else: 
    print("eres menor de edad)
```
## Bucles
Los bucles nso permiten repetir un bloque de código más de una vez.

Un ejemplo es el bucle `for`.

```python
for numero in (0.5):
    print(numero)
```
También podemos recorrer una lista
```python
alumnos = ["Pepe", "manolo", "Juan"]
for alumno in alumnos:
    print(alumno)
```

## Funciones
Las funciones nos permiten guardar un bloque de código con un nombre para llamarlas cuando queramos. Las funciones terminan e paréntesis:
`sumar()`, `jugar()`, etc

Ejemplo:

```python
def calcular():

```