Las funciones son bloques de código que realizan una tarea especifica y pueden ser reutilizados cuando sea necesario. 
### DEFINIR FUNCIONES

Para definirla usamos la palabra clave `def` seguida del nombre de la función y los paréntesis que pueden estar vacíos o contener argumentos.

```python
def saludar (nombre):
		print("Hola, " + nombre)
```

### PARÁMETROS Y ARGUMENTOS

Las funciones pueden tomar cero o más argumentos. Estos argumentos son valores que se le pasan a la función al momento de ser llamada. Pueden ser obligatorio o opcionales dependiendo del resultado que esperes. En el ejemplo anterior "nombre" es un argumento que se le tiene que pasar para que funcione correctamente.

### LLAMADA DE FUNCIONES

Para ejecutar una función se usa el nombre de la función seguido de los paréntesis que pueden o no tener argumentos.

```python
saludar("Juan Pablo")
```


### VALOR DE RETORNO

Las funciones pueden devolver un valor utilizando la palabra `return`. Esto permite que una función calcule un resultado y lo devuelva al punto donde fue llamada.

```python
def suma(a, b)
	return a + b
```

En este caso cuando llamemos la función y dejemos adentro dos números, la función nos devolverá el resultado como suma y ese resultado lo podremos usar como variable.

### FUNCIONES SIN VALOR DE RETORNO

Las funciones pueden no devolver ningún valor de retorno en caso de que solo quisiéramos ejecutar lo que hay dentro de la función y no usar ningún valor dentro de ella.

```python
def imprimirMensaje():
	print("Esto es un mensaje")
```

De esta forma cada que la llamemos solo imprimirá el mensaje y no nos preocuparemos en usar su contenido.