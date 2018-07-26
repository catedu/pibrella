#Salidas de PIBRELLA tipo LED
####¿Cómo se programan las SALIDAS TIPO LED?
Muy fácil:

1. Se crea una variable con el nombre **AddOn**
1. Le asignamos el valor **Pibrella**
1. Enviamos un **mensaje** (broadcast) de la salida de Pibrella que queremos encender o apagar

### ¿Qué mensaje hay que enviar?
Son tan intuitivos que no hace falta explicarlos:

* RedOn
* RedOff
* AmberOn
* AmberOff
* GreenOn
* GreenOff

###Un ejemplo

Vamos a encender el led rojo, el programa sería:

![](/assets/primerprograma.png)

Y el resultado está claro, pero fíjate que se queda encendido, es decir si ahora cambiamos en el programa el mensaje por **GreenOn** y pulsamos la bandera: *¡¡ se encienden los dos* !!!:

![](/assets/PICT0032.JPG)