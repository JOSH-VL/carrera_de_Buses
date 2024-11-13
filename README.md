 # Carrera de Buses 🚌🏆

Este proyecto es un programa en Python que simula una divertida carrera de buses con efectos visuales en la terminal con ASCII. Cada bus avanza aleatoriamente en la pantalla mientras se muestran mensajes divertidos y efectos de color para hacer la carrera más animada.

## Descripción

El programa presenta una competencia entre dos buses, "Lopez" y "Esmeralda", en una pista imaginaria. La carrera dura aproximadamente 25 segundos y muestra mensajes y animaciones para hacerla entretenida, como mensajes intermitentes y cambios de color. Al finalizar, se anuncia el ganador de la carrera.

### Características

- Simulación de avance aleatorio de los buses en cada iteración.
- Efectos de color y formato en la terminal (compatible con terminales que soporten secuencias ANSI).
- Mensajes personalizados que cambian en función del tiempo transcurrido en la carrera.
- Línea de meta que se vuelve verde cuando alguno de los buses llega.

## Requisitos

- Python 3.x
- Compatible con terminales que soporten secuencias de escape ANSI para efectos de color.
- cualquier versión vs code.

## Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local:
    ```bash
    git clone https://github.com/usuario/carrera_de_Buses.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd carrera_de_Buses
    ```

3. Ejecuta el programa con el siguiente comando:
    ```bash
    python carrera_de_buses.py
    ```

## Funcionamiento

El ganador se elige con la función Random, poniendo el ganador aleatoriamente.

Al final, el programa declara un ganador y resalta el nombre del bus que alcanzó primero la meta.

## Ejemplo de Uso

```plaintext
--------------------------------------------------
 _______________  
|__|__|__|__|__|___
|   Lopez       |)
|~~~@~~~~~~~~~@~~~|
==================================================

-------------------------------------
 _______________  
|__|__|__|__|__|___
|   Esmeralda   |)
|~~~@~~~~~~~~~@~~~|
-------------------------------------
