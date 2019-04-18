# BINARY SEARCH

#### Apuntes
 - Binary search solo trabaja con listas ordenadas.
 - Para saber cuanto pasos realizara el algoritmo se usa el logaritmo en base 2
    
    ![logaritmo](https://wikimedia.org/api/rest_v1/media/math/render/svg/9037c6c4f17ed65a90f8dc2db067d74fde2dc66a)
    
    - n = es el total de la cantidad de items en la lista

    ###### Como funciona

    comenzamos creando dos variables
    
    ```
        low = 0 
        high = len(list) - 1
    ```
    estas variables serviran para decidir por donde ir en la lista.
    
    Todo el tiempo revisamos la mitad de la lista, si es el valor que buscamos 
    la funcion nos devolvera la posicion en la que se encuentra el elemento que buscamos
    
    ```
        mid = int((low + high) / 2) 
        guess = list[mid]    
    ```
    Si el elemento es mas pequenio se actualiza la variabe low
    
    ```
        if guess < item:
            low = mid + 1
    ``` 
    Si es mas grande se actualiza la variable high
    
    ```
        if guess > item:
            high = mid - 1
    ```
    
    
    
