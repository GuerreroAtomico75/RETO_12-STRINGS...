# RETO_12-STRINGS...
#### Primer Punto
##### Consulte que hacen los siguientes métodos de strings en python: endswith, startswith, isalpha, isalnum, isdigit, isspace, istitle, islower, isupper.
##### Solución:
Los siguientes métodos que vamos a investigar son:
Aclaración: Los ejemplos están tomados de las páginas web en las que se consultaron la información.
###### endswith:
Este método ayuda a comprobar el final de una cadena con una subcadena; si el final de la cadena y la subcadena son iguales entonces la respuesta booleana será True, sino es así, su respuesta dará false.
Ejemplo:
```python
texto = "¡Hola, mundo!"
resultado = texto.endswith("mundo!")  # Verifica si termina con "mundo!"
print(resultado)  # Esto imprimirá True

resultado = texto.endswith("Hola")  # Verifica si termina con "Hola"
print(resultado)  # Esto imprimirá False
```

###### startswith
Este método ayuda a comprobrar si en el inicio de un string hay un prefijo. Devuelve una respuesta booleana. Al momento de utilizar el método tenemos que poner un argumento, ya que sin argumento el método no funciona. Ya se comprobará en el ejemplo
Ejemplo:
```python
txt = "Bienvenido al curso de Python"

x = txt.startswith("Bien")

print(x)
```

También tenemos en cuenta que se puede poner la posición inicial y final al lado del argumento.

###### isalpha
El método verifica si todos los carácteres del string son letras con un True; si hay números, espacios u otros tipos de carácteres la respuesta es False.
Ejemplo:
```python
cadena = "Hola"
resultado = cadena.isalpha()
print(resultado)  # True
```

Si por algún motivo se utiliza esto con una lista de strings pasa los siguiente:

```python
palabras = ["Manzana", "123", "Banana", "Cereza", "Perro"]

for palabra in palabras:
    if palabra.isalpha():
        print(f"{palabra} es una palabra.")
    else:
        print(f"{palabra} no es una palabra.")
```

Evalúa a cada uno de los strings de la lista

###### isalnum
Este método comprueba si los carácteres que componen al string son alfanuméricos, de ser así tendremos como respuesta un True; de tener un carácter que no sea ni alfabeto ni número entonces nos devolverá un False.

Ejemplo:
```python
texto = "Python123"
resultado = texto.isalnum()
print(resultado)  # True, ya que todos los caracteres son alfanuméricos

texto = "Python 123"
resultado = texto.isalnum()
print(resultado)  # False, ya que hay un espacio en blanco que no es alfanumérico
```

El espacio en blanco no es un carácter alfanumérico, por eso en el segundo caso nos devuelve False.

###### isdigit
Este método comprueba si todos los carácteres de la cadena son dígitos, de ser así el resultado será True; si hay algún carácter diferente al de un dígito entonces será False.

Ejemplo:
```python
txt = "40700"

x = txt.isdigit()

print(x)
```

###### isspace
Este método comprueba si todos los carácteres de la cadena son espacios en blanco, tabulaciones o salto en línea, de ser así el resultado será True; si hay algún carácter diferente a alguno de los anteriores entonces será False.

Ejemplo:
```python
cadena = "   "
resultado = cadena.isspace()
print(resultado)  # True
```

###### istitle
Este método comprueba si la cadena de carácteres está en formato de título, de ser así el resultado será True; si la cadena no respresenta el formato título entonces nos dará False.

Ejemplo:
```python
# Ejemplo 1: Cadena en formato de título
cadena1 = "Una Cadena De Ejemplo"
resultado1 = cadena1.istitle()
print(resultado1)  # True

# Ejemplo 2: Cadena no en formato de título
cadena2 = "esto no es un título"
resultado2 = cadena2.istitle()
print(resultado2)  # False

# Ejemplo 3: Cadena vacía
cadena3 = ""
resultado3 = cadena3.istitle()
print(resultado3)  # False
```

En el último ejemplo es cuando esta vacía, también es falso.

###### islower
Este método comprueba si toda la cadena de carácteres está en minúscula, de ser así el resultado será True; si la cadena tiene alguna mayúscula entonces nos dará False.

Ejemplo:
```python
# Ejemplo 1: Cadena en minúsculas
cadena1 = "hola mundo"
resultado1 = cadena1.islower()
print(resultado1)  # True

# Ejemplo 2: Cadena con mayúsculas
cadena2 = "Hola Mundo"
resultado2 = cadena2.islower()
print(resultado2)  # False

# Ejemplo 3: Cadena con números y símbolos
cadena3 = "123abc"
resultado3 = cadena3.islower()
print(resultado3)  # True, ya que solo verifica letras
```

En el último caso nos damos cuenta que da True porque este método solo verifica los carácteres alfabéticos.

###### isupper
Este método comprueba si toda la cadena de carácteres está en mayúscula, de ser así el resultado será True; si la cadena tiene alguna minúscula entonces nos dará False.

Ejemplo:
```python
texto = "HOLA MUNDO"
resultado = texto.isupper()
print(resultado)  # Resultado: True
```

---

#### Segundo Punto
##### Procesar el archivo y extraer:
* Cantidad de vocales
* Cantidad de consonantes
* Listado de las 50 palabras que más se repiten

##### Solución
...
El link del archivo del reto 12 al usarse no envía ningún archivo, dice que no hay un archivo.
