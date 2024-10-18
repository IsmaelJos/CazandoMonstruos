
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

    El juego mostrara por pantalla un aviso cuando un mounstruo ha sido atrapado y mostrara la posicion de los elementos en el mapa.

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



### [Version 2](https://github.com/IsmaelJos/CazandoMonstruos/tree/V2)

1. Clases principales

    - `Cazador` : Se dedica a moverse por el mapa y lleva la cuenta de la cantidad de mounstruos cazados.

    - `Mapa`: Guarda la posicion de todos los elementos del programa y posee los metodos para cambiar estos.

    - `Mounstruo`: Se dedica a moverse por el mapa.

    - `EventoAleatorio`: Contiene los eventos que pueden ocurrir y son externos a cazador o monstruo.
    
    - `JuegoCazadores`: Inicializa los hilos.

2.  Caracteristicas

    - 

3.  Funcionamiento

    El juego comenzara y cada cierto tiempo los monstruos se moveran de casilla mientras que los cazadores no paran de buscar por todos lados a los monstruos,
    mientras se ejecuta el programa puede aparecer un PoweUp que pueden recojer los cazadores para buscar mas rapido, se representa con una "S".

        ```
            Se ha añadido un powerUp al mapa
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  M  
            C  M  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  C  
            *  *  *  *  *  S  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
        ```

    Si un monstruo se mueve se mostrara una alerta.

        ```
            monstruo1 ha cambiado de sitio
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  M  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  S  *  *  M  C  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  C  *  *  *  *  *  * 
        ```

    Cuando encuentre un cazador a un monstruo se mostrara la posicion de los cazadores y el monstruo restante.

        ```
            cazador1 ha atrapado un monstruo
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  C  *  *  *  
            *  *  *  *  *  *  *  *  *  M  
            *  *  *  *  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
            *  C  *  *  *  *  *  *  *  *  
            *  *  *  S  *  *  *  *  *  *  
            *  *  *  *  *  *  *  *  *  *  
        ```
    
    En el momento en el que termine el tiempo establecido en el codigo el programa terminara mostrando cuantos monstruos han sido capturados.

    ```
        cazador1 ha atrapado 0 monstruos
        cazador2 ha atrapado 1 monstruos
    ```
    