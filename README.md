## Introducción a Phyton
Python es un lenguaje de programación que se destaca por su alto nivel de abstracción, lo que significa que su sintaxis es cercana al lenguaje humano, lo que lo hace fácil de leer y escribir. Fue creado por Guido van Rossum a finales de los 80 y desde entonces ha experimentado un crecimiento exponencial en popularidad y adopción en la comunidad de desarrollo de software. Una de las características distintivas de Python es su enfoque en la legibilidad del código, utilizando espacios en blanco para definir la estructura y los bloques, lo que facilita la comprensión del flujo de control del programa.

Además de su sintaxis clara, Python es conocido por su amplia biblioteca estándar, que proporciona una gran cantidad de módulos y funciones listas para usar que cubren una amplia gama de aplicaciones, desde manipulación de archivos hasta desarrollo web y procesamiento de datos. Esta biblioteca estándar, combinada con su capacidad para integrarse fácilmente con otros lenguajes y herramientas, lo convierte en una opción atractiva para una variedad de proyectos y aplicaciones.

Python es un lenguaje interpretado, lo que significa que no requiere un proceso de compilación previo y puede ejecutarse directamente línea por línea por un intérprete. Aunque esto puede resultar en tiempos de ejecución ligeramente más lentos en comparación con los lenguajes compilados, la facilidad de desarrollo y la capacidad de prototipado rápido que ofrece Python lo convierten en una opción popular para una amplia gama de aplicaciones, desde scripts simples hasta sistemas complejos y aplicaciones de alto rendimiento.

Su naturaleza multiplataforma permite que los programas escritos en Python se ejecuten en una variedad de sistemas operativos, incluyendo Windows, macOS y Linux, lo que lo convierte en una herramienta versátil para desarrolladores y empresas que buscan crear software que pueda ejecutarse en diferentes entornos.

En Python, los tipos de variables se pueden clasificar de la siguiente manera:

Enteros (int): Representan números enteros, por ejemplo, x = 5.

Flotantes (float): Representan números decimales, por ejemplo, y = 3.14.

Cadenas de caracteres (str): Representan texto, por ejemplo, nombre = "Juan".

Booleanos (bool): Representan valores de verdad, True o False, por ejemplo, activo = True.

Listas (list): Colección ordenada y modificable de elementos, por ejemplo, mi_lista = [1, 2, 3, 4].

Tuplas (tuple): Colección ordenada e inmutable de elementos, por ejemplo, mi_tupla = (1, 2, 3, 4).

Diccionarios (dict): Colección no ordenada de pares clave-valor, por ejemplo, mi_dict = {"nombre": "Juan", "edad": 30}.

Conjuntos (set): Colección no ordenada de elementos únicos, por ejemplo, mi_set = {1, 2, 3, 4}.

Las estructuras de control en Python, como los bucles for y while, tienen una sintaxis sencilla y elegante:

Estructura de un bucle for:
python
Copy code
for variable in iterable:
    # Código a ejecutar en cada iteración
variable toma el valor de cada elemento en el iterable.
iterable puede ser una lista, tupla, conjunto, diccionario u otro objeto iterable.
Ejemplo:
python
Copy code
for i in range(5):
    print(i)
Estructura de un bucle while:
python
Copy code
while condición:
    # Código a ejecutar mientras la condición sea verdadera
    # La condición se evalúa en cada iteración
condición es una expresión booleana que se evalúa en cada iteración.
El bucle while se ejecuta siempre que la condición sea True.


## Problemas a resolver
# Ejercicios en clase 
Escribir un programa que lea un entero positivo “n” introducido por el usuario y después muestreen pantalla la suma de todos los enteros desde 1 hasta n . La suma de los primeros enterospositivos puede ser calculada de la siguiente forma

//Problema 1 CLase
barras = int(input("Introduce el número de barras vendidas que no son frescas: "))
precio = 3.49 
descuento = 0.6
coste = barras * precio * (1 - descuento)
print("El coste de una barra fresca es " + str(precio) + "€")
print("El descuento sobre una barra no fresca es " + str(descuento * 100) + "%")
print("El coste final a pagar es " + str(round(coste, 2)) + "€")

Escribir un programa que lea un entero positivo “n” introducido por el usuario y después muestreen pantalla la suma de todos los enteros desde 1 hasta n . La suma de los primeros enterospositivos puede ser calculada de la siguiente forma

//Problema 2 claase
n = int(input("Introduce un numero: "))
suma = n * (n + 1) / 2
print("La suma de los primeros números enteros desde 1 hasta " + str(n) + " es " + str(suma))

Escribir un programa que pregunte al usuario por el número de horas trabajadas y el costo por hora.Después debe mostrar por pantalla la paga que le corresponde.Crea una lista de nombre + sueldo por hora + horas trabajadas de al menos seis operadores.Imprime el nombre y el sueldo a pagar de cada operador.


//Problema 3 clase
horas = float(input("Introduce tus horas de esclavitud: "))
coste = float(input("Introduce tu paga por hora: "))
paga = horas * coste
print("Tu paga es", paga)

# Ejercicios de Tarea

### ¿Cómo compilar?
Se recomienda utilizar Overleaf para compilar el template.

## Template Reporte final (Final_report)
El template contiene diferentes carpetas
* bib Incluye el archivo bibliografia.bib, es recomendable utilizar un gestor de referencias (JabRef, Zotero).
* bst Incluye el el archivo IEEEtran.bst, el cual sirve para darle el estilo de citación de los transactions de IEEE, NO modificar para mantener el formato solicitado.
* codigos Carpeta para agregar los códigos utilizados durante el proyecto, NO se recomienda colocar todo el código en el cuerpo del documento, para eso utilizar los anexos.
* Imagenes Carpeta para colocar las imágenes utilizadas en el documento, se recomiendo utilizar .eps.

El documento main.tex se encuentra comentado para su mejor comprensión.

### ¿Cómo compilar?
Al igual que en el caso anterior, se recomienda utilizar Overleaf.

## Template Entrega individual
El documento individual debe ser anónimo y redactado en inglés.
El template contiene una carpeta
* Imagenes: Carpeta para colocar las imágenes usadas en el reporte, se recomienda .eps o .png

### ¿Cómo compilar?
Se recomienda utilizar Overleaf.

