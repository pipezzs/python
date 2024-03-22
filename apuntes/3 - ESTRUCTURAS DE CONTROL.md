Las estructuras de control nos permiten controlar el flujo la ejecución, son muy importantes tanto en Python como en cualquier lenguaje de programación. 
### BUCLE IF-ELSE

Esta estructura nos permite ejecutar acciones según las condiciones que se cumplan o no.

```python
if condicion1:
	print("Ejecutar en caso de cumplir condición número 1")
elif condicion2:
	print("Ejecutar en caso de no cumplir la condición 1 pero si la 2")
else:
	print("Ejecutar en caso de no cumplir ninguna condición")
```

Su flujo de ejecución es de arriba hacia abajo, osea que siempre se ejecutará el `if` antes que el `else`.

### BUCLE WHILE

Esta estructura nos permite que mientras la condición de `While` sea verdadera se siga ejecutando una y otra vez hasta que esa condición sea falsa.

```python
condicion = True

while condicion:
    print("Diamante")
```

En este caso se imprimirá la palabra "Diamante" en la consola indefinidamente, combinando con estructuras como `if-else` podemos hacer cosas interesantes como por ejemplo apagar su función si escribimos con un `input` una palabra especifica.

```python
condicion = True

while condicion:
    contraseña = input ("Ingresa la contraseña")
    if contraseña == "123":
        condicion = False
```

Aplicando lo aprendido se aprecia un pequeño programa que verifica si la contraseña es correcta o incorrecta.

### BUCLE FOR

El bucle `for` es usado para hacer una acción un número determinado de veces o para iterar sobre una lista. Es muy importante entenderlo y se suele usar en muchos lenguajes de programación. La siguiente instrucción imprimirá los números de 0 al 4 (Esto es porque la iteración empieza por 0). 

```python
for i in range (5):
    print(i)
```

La siguiente instrucción iterara sobre una lista imprimiendo todos sus elementos

```python
texto = ["leon", "sandia", "melon", "lapiz", "oscuro", "diente"]
for palabra in texto:
	print (palabra)
```

### CONTROL DE BUCLES

Para controlar un bucle en un programa existen condiciones las cuales pueden alterar el flujo y dar el resultado esperado.

**Break:** Esta función nos permite salir prematuramente del bucle.

```python
condicion = True

while condicion:
    print("Pinguino")
    break
```

En este caso después de imprimir una vez "Pinguino" el bucle ejecutara `break` lo cual lo sacara automáticamente del bucle.

**Continue:** Esta función nos permite saltar una iteración para continuar a la siguiente.

```python
for i in range(5):
    if i == 2:
        continue
    print(i)
```

En este caso el código imprimirá la secuencia de números de 0 al 4 pero como el `if` remarca que si `i`  es igual a 2 el código ejecutará un `continue` se escribirá una secuencia como esta: 0, 1, 3, 4.