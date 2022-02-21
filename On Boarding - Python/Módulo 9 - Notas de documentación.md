# **MÓDULO 9**
> Uso de funciones en Python.

Las funciones en python permiten la reutilización de ciertas estructuras de instrucciones para evitar escribir varias veces el mismo conjunto de instruccinoes. Las funciones son la base para crear estructuras de datos tales como Grafos, Union-Find, Segment tree, etc.

Las funciones, además, permiten la unión de datos de entrada y salida de otras funciones, lo cual produce que una función pueda llamar a más de una función. 

## Contexto de la misión

Se creará un programa para poder escribir y obtener un informe sobre la información precisa de un cohete espacial.

## _**Documentación sobre funciones**_

### **Función en Python**
Ua función en Python es un conjunto de instrucciones que siempre va a devolver un dato, ya sea algo vacío o algo relevante para la situación. La entrada de datos de uan función, parámetros, se podrá hacer obligatoria u opcional.

### Ventajas de usar funciones
* Logran hacer el código más pequeño.
* El uso de funciones suele hacer al código más fácil de leer.
* Permite realizar uan depuración más fácil.

### Desventajas
* Puede llegar a limitar el código.


### **Syntaxis de una función** 
En los lenguajes de programación, al menos en la mayoría, se permite tener en consideración 4 diferentes tipos de funciones. 

* Función sin parámetros y no regresa nada.
* Función con parámetros y no regresa nada.
* Función sin parámetros y regresa un valor.
* Función con parámetros y regresa un valor.

> Nota: los parámetros y argumentos hace referencia a los valores que se debe de pasar desde el main, puesto que estos valores son los necesitados para hacer que el función se ejecute.

Para escribir una función se sigue lo siguiente:

 ```python 
 def nombre_función( parámetros o argumentos ):
     instrucciones.
     return 
 ```

De modo que dentro del código principal para poder hacer uso de estas funciones se deben de invocar o mandarlas a llamar, para esto se debe de tener en cuenta cuando se regresa un elemento o cuando no se regresa nada.

```python
salida = funcion(parámetros o void) # Cuando regresa algo.
funcion(parámetros o void)          # Cuando no regresa nada.
```
_Algo importante de tener en cuenta es que cuando la función no regresa nada y aún así le asignamos una variable lo que obtenemos es _None_. No obstante, si no regresa nada no será necesario específicar tal cosa._


### **Parámetros** 
Cuando una función es invocada se puede distinguir tres cosas:
* En caso de que no reciba argumentos entonces los paréntesis quedan vacíos:
    
    ```python
        # Para esto será necesario ver que como un ejemplo una función que solo 
        # imprime:

        def saludo():
            print("Hola")
        
        # Main
        saludo()
    ```


* Si recibe argumentos los paréntesis quedan llenos de estos.
    ```python
        # Podríamos verlo como una función que devuelve la suma de dos enteros.

        def suma(a,b):
            return a+b
        
        # Main
        resultado = 0
        resultado = suma(1,2)
    ```
No osbtante en este tipo de funciones al no ingresar valores es posible obtener una excepción por falta de argumentos.
Las entradas obligatorias reciben el nombre de argumentos.

     ```python
        # Para esto será necesario ver que como un ejemplo una función que solo 
        # imprime:

        def saludo():
            print("Hola")
        
        # Main
        suma()
        Traceback (most recent call last):
        File '<stdin>', line 1, in <module>
        TypeError: any() takes exactly one argument (0 given)
        # Indica que se neecsita mínimo un argumento.
    ```
* Los argumentos son opcionales

    Es posible usar argumentos opcionales por medio de la incorporación de la función str, la cual va a permitir ir construyendo la solución a partir de los datos dados. En caso de no tener nada simplemente devuelve nada.

### **Uso de más de un parámetro**
Para hacer que la función pueda usar más de un parámetro se deberá de indicar al momento de crear una función, de modo que los parámetros son separados por comas.

def funcion(a,b): ...

### **Uso de funciones como argumentos de otras funciones**
Recordamos que el uso de round() o de min/max como funciones, por ende si nosotros usamos lo siguiente:

```python
    def division(a,b):
        return a/b
    
    print( round(division(120,51)) )
```

Sería usar esa función de división como argumento para la función de redondeo.
> Nota: tener en cuenta que usar funciones como argumentos puede hacer que el código sea menos fácil de leer, y más cuando con varios argumentos.




