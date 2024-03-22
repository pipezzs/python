La manipulación de cadenas es una tarea común y hay varias operaciones se pueden realizar.

### CONCATENACIÓN
 
Puedes unir dos o más cadenas usando el operador `+`
```python
cadena1 = "Hola"
cadena2 = "Mundo!"
union = cadena1 + " " + cadena2
print (union) ## RESULTADO: Hola Mundo!
```
### LONGITUD

Puedes obtener la longitud de una cadena usando la función `len()`

```python
cadena = "Aguacate"
longitud = len(cadena)
print (longitud) ## RESULTADO: 8
```
### INDEXACIÓN Y SEGMENTACIÓN

Puedes acceder a caracteres individuales de una cadena utilizando indexación y obtener subcadenas usando segmentación.

```python
cadena = "Python"
indexacion = cadena[0]
subcadena = cadena[1:4]
print(indexacion) ## RESULTADO: P
print (subcadena) ## RESULTADO: yth
```
### MÉTODOS DE FORMATO

Puedes formatear una cadena usando métodos como `format()` o f-strings

*format():*
```python
nombre = "Juan"
edad = 30
saludo = "Hola, me llamo {} y tengo {} años".format(nombre, edad)
print (saludo) ## RESULTADO: Hola me llamo Juan y tengo 30 años
```

*f-strings:*
```python
nombre = "Juan"
edad = 30
saludo = f"Hola, me llamo {nombre} y tengo {edad} años"
print (saludo) ## RESULTADO: Hola me llamo Juan y tengo 30 años
```
### MÉTODOS DE BUSQUEDA Y REEMPLAZO

Puedes buscar subcadenas dentro de una cadena y remplazarlas utilizando métodos como `find()`, `replace()` o `count()`.

```python
cadena = "Hola! como estas Alfredo"

indice = cadena.find("estas")
print(indice) ## RESULTADO: 11

conteo = cadena.count("como")
print(conteo) ## RESULTADO: 1

nueva_cadena = cadena.replace("Alfredo", "Lionel")
print(nueva_cadena) ## RESULTADO: Hola! como estas Lionel
```
### METODOS DE TRANSFORMACIÓN

Puedes convertir una cadena a mayúsculas, minúsculas o capitalizarla utilizando métodos como `upper()`, `lower()` y `capitalize()`.

```python
cadena = "la MusiCa es divErtida"
mayusculas = cadena.upper()
minusculas = cadena.lower()
capitalizada = cadena.capitalize()
print(mayusculas)   ## RESULTADO: LA MUSICA ES DIVERTIDA
print(minusculas)   ## RESULTADO: la musica es divertida
print(capitalizada) ## RESULTADO: La musica es divertida
```
