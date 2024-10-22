
# Cazando Monstruos

### [Version 1](https://github.com/IsmaelJos/CazandoMonstruos/tree/V1)



1. Clases principales

    - `Cazador` : Se dedica a moverse por el mapa y lleva la cuenta de la cantidad de mounstruos cazados.

    - `Mapa`: Guarda la posicion de todos los elementos del programa y posee los metodos para cambiar estos.

    - `Mounstruo`: Se crea y existe.
    
    - `JuegoCazadores`: inicializa los hilos.

2.  Caracteristicas

    - El unico hilo que se lanza es el cazador, a mas hilos mas cazadores buscando.

3.  Funcionamiento

    El juego mostrara por pantalla un aviso cuando un mounstruo ha sido atrapado y mostrara la posicion de los elementos en el mapa

    ```
        cazador2 ha atrapado un monstruo
        C  *  *  *  M  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  C  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *  
        *  *  *  *  *  *  *  *  *  *
    ```

    En el momento en el que termine el tiempo establecido en el codigo el programa terminara mostrando cuantos monstruos han sido capturados

    ```
        cazador1 ha atrapado 0 monstruos
        cazador2 ha atrapado 1 monstruos
    ```

