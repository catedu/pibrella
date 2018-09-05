#Entradas

>Nota: En la manipulación de las entradas y salidas **CONECTA PIBRELLA CON SU PROPIA ALIMENTACIÓN USB**

Pibrella tiene 4 entradas ABCD que se controlan con la instrucción:

![](/assets/tambor-buzzer1.png)

Donde A puede ser las otras letras BCD y el valor 1 es cuando están cortocircuitados los dos pines de A, por lo tanto el valor 0 corresponde cuando están en abierto.

Internamente son interruptores en configuración [pull-up](https://catedu.gitbooks.io/programa-arduino-mediante-codigo/content/resistencias_pullup_y_pulldown.html) donde la masa es el pin más interno y la tensión de alimentación es 3.3V:

![](/assets/pull.png)

Vamos a modificar el tambor :

{% youtube %}https://www.youtube.com/watch?v=V1W2cEvKlF4&feature=youtu.be{% endyoutube %}

¿Te atreves?

%accordion%Solución%accordion%

El archivo lo tienes en https://github.com/JavierQuintana/pibrella

Hacemos dos actuaciones diferentes, decir *Hola* y *buzzer*, según el evento de InputA valga 0 o 1:

![](/assets/tambor-buzzer2.png)

%/accordion%

