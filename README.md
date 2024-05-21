# Stacker - Opción 1 - Logisim

![Stacker](https://github.com/santiago-salinas/Stacker/assets/48341470/bb214b72-87b3-4e14-8495-4a6abc4b29da)

El obligatorio consiste en la realización en logisim de la simulación de un juego de feria (arcade) llamado Stacker. El objetivo del juego es construir una plataforma que llegue a lo alto de la pantalla, la dificultad del mismo se halla en que se debe construir en niveles mientras se deslizan las plataformas.
 
- Nuestra implementación contará con
- Display 7x10.
- Un Pulsador 
- Un Contador Binario de Puntaje
- Un Cronómetro

El pulsador permite ubicar el piso en movimiento en cualquier posición horizontal. Nosotros, para simplificar el trabajo, comenzaremos todas las partidas con una base de tres bloques ubicada en el centro. Tal que al iniciar el juego tendremos un primer nivel de plataforma que se moverá de forma horizontal sobre la base hasta que accionamos el pulsador. 

![image](https://github.com/santiago-salinas/Stacker/assets/48341470/e0ce8dbd-dacc-427b-97d8-5d4151a0d192)

Al accionar el pulsador únicamente aquellas piezas que queden sobre la base anterior, se mantendrán en juego. La plataforma deslizante del siguiente nivel contará con las mismas cantidades de piezas que el nivel anterior. Es decir, si el nivel anterior perdió un bloque, el siguiente nivel tendrá un bloque menos. 

![image](https://github.com/santiago-salinas/Stacker/assets/48341470/7b43cc8c-b682-4348-aab8-caf9d7ecbcbd)

El proceso de acumular niveles se hará un total de 10 veces y el resultado final será la suma de todos los bloques que están en juego, y su debido multiplicador bonificador según el piso. Este resultado se debe mostrar en un contador binario.

![image](https://github.com/santiago-salinas/Stacker/assets/48341470/9af83d1a-a150-4d60-8c15-a16e413f4513)

El juego frena (y por consiguiente el cronómetro), cuando se llega a la última fila, o al ubicar un piso, si ningún bloque se alinea con el piso de abajo.

Cronómetro:

![image](https://github.com/santiago-salinas/Stacker/assets/48341470/98ddfd62-7dff-4968-888c-11d830622fc0)

Se pide desarrollar la lógica en base a compuertas necesaria para lograrlo, recuerde que a su disposición cuenta con las siguientes herramientas
- Tablas de verdad
- Mapas de Karnaugh
- Máquinas de estado
- Túneles (Logisim)

Deberá documentar todo el proceso creativo que el equipo fue incurriendo hasta la entrega. Rogamos dibujar un plan de acción previo a su codificación en circuitos, esto ayudará a tener una idea general del objetivo y que rol cumplirá cada módulo.

Ayudas visuales

![image](https://github.com/santiago-salinas/Stacker/assets/48341470/a12ac4ad-b3d6-4f6b-9f8f-928e70827c73)
