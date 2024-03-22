En Python existen varias colecciones de datos que se utilizan para almacenar y manipular datos de diferentes maneras. 

### LISTAS

Una lista en una colección de datos ordenada con elementos mutables. Los elementos de las listas pueden ser de diferentes tipos y se acceden mediante índices.

```python
lista = [1,"venado",3.5,4,"oso"]
```

### TUPLAS

Una tupla es similar a una lista pero es inmutable, esto quiere decir que no se puede modificar ningún elemento.

```python
tupla = ("esfero",2,"cien",4,8)
```

### CONJUNTOS

Un conjunto es una colección de datos desordenada con elementos mutables y valores únicos. Los conjuntos no permiten valores duplicados.

```python
conjunto = {7,22.5,"ciervo",8,5}
```

Los conjuntos admiten cualquier tipo de valor siempre y cuando sea un tipo *hashable*, esto quiere decir que no pueden contener listas y diccionarios ya que son mutables.

### DICCIONARIOS

Los diccionarios son una colección de datos desordenada de pares (valor-clave). Se accede a cada elemento mediante su clave en lugar de un índice numérico.

```python
diccionario = {"clave1": valor1, "clave2": valor2, "clave3": valor3}
```
