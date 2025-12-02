
## Mini Arcade en Python

Un pequeño arcade interactivo creado en Python que reúne varios minijuegos clásicos.
Este proyecto es ideal para practicar conceptos básicos de programación como funciones, ciclos, condicionales, manejo de entradas y generación de números aleatorios.
## Juegos incluidos
1. Adivina el número
El programa genera un número aleatorio entre 1 y 10.
El jugador intenta adivinarlo y el sistema indica si acertó o no.

2. Par o impar
El usuario ingresa un número y el programa determina si es par o impar utilizando el operador módulo (%).

3. Cara o sello
Se simula el lanzamiento de una moneda.
El usuario escoge "cara" o "sello" y se compara con el resultado obtenido al azar.

4. Piedra, papel o tijera
  El jugador selecciona una opción, la computadora selecciona otra aleatoriamente.
  Se evalúan las reglas clásicas para determinar si el jugador gana, pierde o empata.
  
5. Ruleta 1–5
  El usuario elige un número del 1 al 5.
  El programa genera uno al azar y determina si coincide con la elección del jugador.

## Lógica general del programa

Cada juego está implementado como una función independiente para asegurar modularidad y claridad.
El menú principal utiliza un ciclo while que se repite hasta que el usuario elige Salir.
Se emplea la librería random para los elementos de azar.
Las entradas del usuario son validadas para evitar errores.
El código está diseñado para ejecutarse directamente en consola o en Google Colab

## Objetivo del proyecto
  Este mini arcade fue creado como práctica de:
  Manejo de funciones
  Control de flujo
  Programación modular
  Juegos simples con lógica básica
  Interacción directa con el usuario
