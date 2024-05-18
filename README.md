# Problemas de Programación y Algoritmos de Ordenación

Este repositorio contiene soluciones para los siguientes problemas de programación:
1. Búsqueda del elemento mayor y menor en un arreglo.
2. Ordenar un arreglo utilizando los algoritmos Bubble Sort y Selection Sort.

## Contenidos

- `mayor_menor.py`: Encuentra y muestra el número mayor y el número menor de una lista ingresada por el usuario.
- `bubble_sort.py`: Implementación del algoritmo Bubble Sort para ordenar una lista.
- `selection_sort.py`: Implementación del algoritmo Selection Sort para ordenar una lista.

## Ejecución del Código

### Búsqueda del Elemento Mayor y Menor

1. **Instrucciones**:
    - Ejecuta el archivo `mayor_menor.py`:
        ```sh
        python mayor_menor.py
        ```
    - Ingresa la cantidad de números que deseas incluir en la lista.
    - Ingresa cada número cuando se te solicite.
    - El programa mostrará la lista completa, el número mayor y el número menor.

2. **Ejemplo**:

    **Entrada del Usuario**:
    ```
    Cuantos números desea ingresar? 5
    1 Ingrese un numero: 10
    2 Ingrese un numero: 3
    3 Ingrese un numero: 25
    4 Ingrese un numero: 7
    5 Ingrese un numero: 19
    ```

    **Salida**:
    ```
    Lista: 
    [10, 3, 25, 7, 19]
    Numero mayor:  25
    Numero menor:  3
    ```

### Bubble Sort

1. **Instrucciones**:
    - Ejecuta el archivo `bubble_sort.py`:
        ```sh
        python bubble_sort.py
        ```
    - El programa ordenará la lista utilizando el algoritmo Bubble Sort y mostrará el resultado.

2. **Ejemplo**:

    **Código**:
    ```python
    print(bubble([3, 5, 1, 2, 9, 7, 4, 8, 6]))
    ```

    **Salida**:
    ```
    [1, 2, 3, 4, 5, 6, 7, 8, 9]
    ```

### Selection Sort

1. **Instrucciones**:
    - Ejecuta el archivo `selection_sort.py`:
        ```sh
        python selection_sort.py
        ```
    - El programa ordenará la lista utilizando el algoritmo Selection Sort y mostrará el resultado.

2. **Ejemplo**:

    **Código**:
    ```python
    print(selectionSort([3, 4, 9, 2, 1, 8, 5, 7, 6]))
    ```

    **Salida**:
    ```
    [1, 2, 3, 4, 5, 6, 7, 8, 9]
    ```
