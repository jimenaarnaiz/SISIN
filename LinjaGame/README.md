# Juego de Linja

Juego de mesa estratégico para dos jugadores. A continuación se resumen las reglas principales y detalles del funcionamiento del juego.

## 📋 Descripción del juego

**Linja** es un juego abstracto que representa un combate entre dos monjes que avanzan por un camino de bambú dividido en líneas. El objetivo es llegar lo más lejos posible en el campo del oponente con la mayor cantidad de fichas.

## 🎯 Objetivo

Al final del juego, cada jugador obtiene puntos en función de la línea en la que se encuentren sus fichas. El jugador con más puntos gana la partida.

## 🧩 Componentes

- Tablero dividido en 7 líneas verticales.
- Cada jugador comienza con **6 fichas** del mismo color.

## 🕹️ Reglas básicas

1. Cada jugador coloca sus fichas en la primera línea de su lado del tablero (línea 1 para un jugador, línea 7 para el otro).
2. En su turno, un jugador:
   - Mueve una ficha a la siguiente línea disponible.
   - El número de fichas que puede mover depende del número de fichas en la línea donde se encuentra la ficha más adelantada.
3. No se puede saltar una ficha rival.
4. El juego termina cuando todas las fichas han llegado a la última línea.

## 🧮 Puntuación

- Cada línea tiene un valor de puntos (por ejemplo: línea 1 = 1 punto, línea 2 = 2 puntos, ..., línea 7 = 7 puntos).
- Se suman los puntos de todas las fichas de cada jugador según su posición al final.
- Gana quien tenga la puntuación total más alta.
