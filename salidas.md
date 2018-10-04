#Salidas
La **ventaja** de Pibrella es que podemos conectar diréctamente un pequeño motor, led, servo... son salidas tipo interruptor, que conecta con alimentación de 5V o no conecta con alimentación 0V y cada salida tiene sus dos terminales, no comparten masa.

Las instrucciones son sencillas: 
* Para encender la salida E: Enviar el mensaje **OutputEon**
* Para apagar la salida E: Enviar mensaje **OutputEoff**

Os dejamos a vuestra imaginación cuales serían los mensajes para las otras 3 salidas **F, G y H**.

Vamos a utilizarlo para mover un pequeño coche, así damos movimiento a nuestra pibrella.

La desventaja es que no puede invertir la polaridad, luego no podemos mover nuestro coche hacia atrás.

Por menos de 7€ se puede conseguir un sencillo chásis (no hace falta el soporte pilas)

![](/assets/coche.png)

Vamos a realizar un pequeño "coche teledirigido"

{% youtube %}https://www.youtube.com/watch?v=qQ4ugkmEaqA&feature=youtu.be{% endyoutube %}

¿Te atreves?

%accordion%Solución%accordion%

El archivo lo tienes en https://github.com/JavierQuintana/pibrella como coche1

Primero conectamos cada motor en una de los conectores salida de la Pibrella, nosotros lo vamos a conectar en el E y en el H:

![](/assets/conexionmotores.jpg)

Ponemos la raspberry en el chasis con una goma elástica y encedemos **cuidado, no encima de la rueda loca pues provocarías cortocircuitos con los tornillos y la placa raspberry !!!**

![](/assets/conexionmotores2.jpg)

Y el programa es sencillo:

![](/assets/programaCoche1.png)

¡¡Acuerdate de activiar GPIOServer !!!

%/accordion%



