# ejemplo-react
Demo de react

La función Square recibe value y onSquareClick como entradas, y se encarga de crear un boton de nombre de clase square y que al ser presionado, de un valor.

La función Board decidirá si hay un ganador o no, de no ser así, el juego continuará con el siguiente jugador y su diferente signo, además de asignar los valores a cada cuadrado del juego.

La función handleClick recibe un valor i, además nos indicará si el juego ha terminado, el movimiento ha sido repetido de casilla o si hay un nuevo movimiento.

La función game visualiza el historial de movimientos y los muestra en pantalla como movimientos posible a regresar con ayuda de las funciones handlepLay y jumpTo, neceserias para actualizar el historial y moverse de un movimiento a otro.

La función calculateWinner, donde se definirán las combinaciones en as cuales se decide un ganador en lines, además comprobará si todas las casilla de una línea tienen el mismo valor, de ser así, se retornará el valor ganador.