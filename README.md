# Introducción a Phyton
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


# Problemas a resolver
## Ejercicios en clase 
### Ejercicio 1
Escribir un programa que lea un entero positivo “n” introducido por el usuario y después muestreen pantalla la suma de todos los enteros desde 1 hasta n . La suma de los primeros enterospositivos puede ser calculada de la siguiente forma

//Problema 1 CLase

barras = int(input("Introduce el número de barras vendidas que no son frescas: "))

precio = 3.49 

descuento = 0.6

coste = barras * precio * (1 - descuento)

print("El coste de una barra fresca es " + str(precio) + "€")

print("El descuento sobre una barra no fresca es " + str(descuento * 100) + "%")

print("El coste final a pagar es " + str(round(coste, 2)) + "€")

### Ejercicio 2

Escribir un programa que lea un entero positivo “n” introducido por el usuario y después muestreen pantalla la suma de todos los enteros desde 1 hasta n . La suma de los primeros enterospositivos puede ser calculada de la siguiente forma

//Problema 2 claase

n = int(input("Introduce un numero: "))

suma = n * (n + 1) / 2

print("La suma de los primeros números enteros desde 1 hasta " + str(n) + " es " + str(suma))

### Ejercicio 3

Escribir un programa que pregunte al usuario por el número de horas trabajadas y el costo por hora.Después debe mostrar por pantalla la paga que le corresponde.Crea una lista de nombre + sueldo por hora + horas trabajadas de al menos seis operadores.Imprime el nombre y el sueldo a pagar de cada operador.



//Problema 3 clase

horas = float(input("Introduce tus horas de esclavitud: "))

coste = float(input("Introduce tu paga por hora: "))

paga = horas * coste

print("Tu paga es", paga)

## Ejercicios de Tarea
### Ejercicio 1

1.-• Crea una lista llamada numeros que contenga al menos 10 números.• Calcula el promedio de los números pares y el producto de los números impares.• Imprime los resultados

//Problema 1. Tarea

numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]  # Lista de números

#Inicia las variables para calcular el promedio de los números pares y el producto de los números impares

suma_pares = 0

cantidad_pares = 0

producto_impares = 1

#Iteramos sobre la lista de números

for numero in numeros:
    
    if numero % 2 == 0:  # Si el número es par
        
        suma_pares += numero  # Agregamos el número a la suma de pares
    
        cantidad_pares += 1  # Incrementamos el contador de pares
    
    else:

        producto_impares *= numero  # Multiplicamos el número al producto de impares

#Calculamos el promedio de los números pares

if cantidad_pares != 0:

    promedio_pares = suma_pares / cantidad_pares

else:

    promedio_pares = 0


#Imprimimos los resultados

print("Promedio de los números pares:", promedio_pares)

print("Producto de los números impares:", producto_impares)

### Ejercicio 2

2.- Crea un programa que solicite al usuario adivinar un número secreto. El programa debe generarun número aleatorio entre 1 y 10, y el usuario debe intentar adivinarlo. El programa debeproporcionar pistas si el número ingresado por el usuario es demasiado alto o bajo. El bucle whiledebe continuar hasta que el usuario adivine correctamente. Al final se debe imprimir en cuantosintentos el usuario logró adivinar el número.Pista:import random# Generar un número aleatorio entre 1 y 10numero_secreto = random.randint(1, 10)

//Problema 2 de Tarea

import random

numero_secreto = random.randint(1, 10)  # Generar un número aleatorio de 1 y 10

intentos = 0  # Inicia el contador de intentos

print("Bienvenido al adivina quien de los numeros")

while True:

    intento = int(input("Adivina el número secreto: "))  # Solicita al usuario que ingrese un número

    intentos += 1  # Incrementar el contador de intentos

    if intento == numero_secreto:
        print("¡Felicidades! Has adivinado el número secreto en", intentos, "intentos.")
        break  # Salir del bucle while si el usuario adivinó el número
    elif intento < numero_secreto:
        print("El número esta bajo. Intenta de nuevo.")
    else:
        print("El número esta alto. Intenta de nuevo.")

### Ejercicio 3

3.- Robot exploradorEl programa debe generar una matriz de al menos 5x5.El robot inicia su camino en la posición (0,0) de la matriz y debe salir en la posición (4,4) o lamáxima posición si se cambia el tamaño de matriz.El numero y la posición de los obstáculos es aleatoria.El robot solo puede avanzar, girar a la izquierda o a la derecha para buscar un camino libre, en eleventual caso que el robot no pueda salir debe imprimir en pantalla “Imposible llegar al destino”En caso de que el robot llegue a su destino final deberá imprimir el mapa, con los espacios libres yobstáculos de la siguiente forma X obstáculo o libreo o o X oo o o o oo o o o Xo o o o oo X X X oDeberá imprimir también la ruta que siguió.Mostrar un segundo mapa con el “camino” seguido por el robot mediante flechas
Pista:Flecha hacia arriba: ↑ (U+2191)Flecha hacia abajo: ↓ (U+2193)Flecha hacia la izquierda: ← (U+2190)Flecha hacia la derecha: → (U+2192)

//Problema 3 de Tarea 

import random

#Definir constantes para las direcciones

UP = 0

RIGHT = 1

DOWN = 2

LEFT = 3

#Definir los símbolos para el mapa

FREE = 'o'

OBSTACLE = 'X'

ROBOT = '*'

PATH = '.'

#Definir las flechas

ARROW_UP = '↑'

ARROW_DOWN = '↓'

ARROW_LEFT = '←'

ARROW_RIGHT = '→'

#Tamaño de la matriz

ROWS = 5

COLS = 5

#Función para imprimir la matriz

def print_matrix(matrix):

    for row in matrix:
    
        print(' '.join(row))



#Función para generar la matriz con obstáculos aleatorios

def generate_matrix(rows, cols):

    matrix = [[FREE for _ in range(cols)] for _ in range(rows)]
    
    obstacles = random.sample(range(rows * cols), random.randint(1, rows * cols // 2))
    
for obstacle in obstacles:

        row = obstacle // cols
        
        col = obstacle % cols
        
        matrix[row][col] = OBSTACLE
    
    return matrix


#Función para verificar si la posición está dentro de la matriz

def is_valid_move(matrix, row, col):

    return 0 <= row < len(matrix) and 0 <= col < len(matrix[0])



#Función para encontrar el camino

def find_path(matrix):

    directions = [(0, 1), (1, 0), (0, -1), (-1, 0)]  # Derecha, Abajo, Izquierda, Arriba
    
    path = []
    
    row, col = 0, 0
    
    direction = RIGHT
    
    while True:
    
        if (row, col) == (len(matrix) - 1, len(matrix[0]) - 1):
        
            break
        foun
        
        d = False
        
        for _ in range(4):
        
            new_direction = (direction + _) % 4
            
            new_row, new_col = row + directions[new_direction][0], col + directions[new_direction][1]
            
            if is_valid_move(matrix, new_row, new_col) and matrix[new_row][new_col] == FREE:
            
                matrix[row][col] = PATH
                
                path.append((row, col))
                
                row, col = new_row, new_col
                
                direction = new_direction
                
                found = True
                
                break
       
        if not found:
        
            if path:
            
                matrix[row][col] = PATH
                
                row, col = path.pop()
            
            else:
            
                return None
    
    path.append((row, col))
    
    return path

#Función para imprimir el camino que el robot va a seguir

def print_path(matrix, path):

    for i in range(len(path) - 1):
    
        current_row, current_col = path[i]
        
        next_row, next_col = path[i + 1]
        
        if current_row == next_row:
        
            if current_col < next_col:
            
                matrix[current_row][current_col] = ARROW_RIGHT
            
            else:
            
                matrix[current_row][current_col] = ARROW_LEFT
        
        else:
        
            if current_row < next_row:
            
                matrix[current_row][current_col] = ARROW_DOWN
            
            else:
            
                matrix[current_row][current_col] = ARROW_UP
   
    matrix[path[-1][0]][path[-1][1]] = ROBOT

#Genera la matriz

matrix = generate_matrix(ROWS, COLS)

path = find_path(matrix)

#Imprime la matriz original

print("Mapa original:")

print_matrix(matrix)

print()

if path:
  
    # Imprimir el mapa con la ruta del robot
    
    print("Mapa con la ruta del robot:")
    
    print_path(matrix, path)
    
    print_matrix(matrix)

else:

    print("Imposible llegar al destino")
