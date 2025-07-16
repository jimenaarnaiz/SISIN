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
2. En su turno, un jugador tiene 2 movimientos:
   En el primer movimiento, el jugador avanza una de sus fichas una casilla. El número de fichas que ya había en esa casilla (sin contar la que se acaba de mover) determina cuántas casillas podrá avanzar otra ficha en su segundo movimiento
3. No se puede saltar una ficha rival.
4. En cada *fila* solamente puede haber un **máximo de $6$ fichas**, en total, contando el conjunto de las rojas y las negras.
5. **La partida finaliza cuando las fichas de ambos jugadores se han sobrepasado completamente**. Es decir: Las fichas rojas quedan a un lado del tablero y las negras a otro, sin mezclarse.

## 🎇 Turno extra

Si en su segundo movimiento un jugador desplaza una ficha a una casilla vacía, dicho jugador obtendrá un turno extra completo.

Si en su turno extra, el jugador desplaza de nuevo en su segundo movimiento una ficha a una casilla vacía, deberá pasar turno. Es decir, un mismo jugador no puede contar con dos turnos extra seguidos.

Si un jugador mueve a una casilla vacía en su movimiento inicial pierde su segundo movimiento, pero si hace lo mismo en su segundo movimiento es premiado con un turno extra.

## 🧮 Puntuación

- Cada línea tiene un valor de puntos (por ejemplo: línea 1 = 1 punto, línea 2 = 2 puntos, ..., línea 7 = 7 puntos).
- Se suman los puntos de todas las fichas de cada jugador según su posición al final.
- Gana quien tenga la puntuación total más alta.
