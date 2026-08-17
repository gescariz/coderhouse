# coderhouse

# Ejercicio 1 - Exploración de estructuras de datos en Python (Listas, Tuplas, Sets y Diccionarios)

## Propósito
Practiqué la creación, identificación y manipulación básica de estructuras fundamentales en Python para entender sus diferencias de comportamiento: **mutabilidad vs inmutabilidad** y **cómo se accede a los datos**.

## Qué aprendí: Lista vs Tupla
- **Lista (`list`)**: es **mutable**, por eso permite modificar elementos mediante índices (ej: `mi_lista[0] = ...`).
- **Tupla (`tuple`)**: es **inmutable**, por eso **no permite reasignar** elementos. Al intentar hacerlo (ej: `mi_tupla[0] = 10.5`) Python lanza un error del tipo `TypeError`.

## Qué hice en el ejercicio
- Creé:
  - una **lista** con 3 películas favoritas,
  - una **tupla** con coordenadas (latitud, longitud),
  - un **set** con 3 lenguajes (incluyendo uno repetido para observar la eliminación de duplicados),
  - un **diccionario** que representa un libro (título, autor, año).
- Verifiqué el tipo de cada estructura con `type(...)`.
- Accedí el primer elemento de la lista usando índices.
- Intenté modificar la tupla para observar el error (dejando esa línea comentada para que el programa corra).
- Mostré cómo el set elimina duplicados y que no conserva orden para acceso por índice.

