#1 CONFIGURAR TU RASBERRY

Necesitas hacer estos pasos:

1. **INSTALAR EL SISTEMA OPERATIVO RASPBIAN** [aquí cómo hacerlo](https://catedu.gitbooks.io/raspberry-muy-basico/content/3-raspbian.html) y por supuesto saber apagarlo correctamente ([aquí](https://catedu.gitbooks.io/raspberry-muy-basico/content/7-apagar.html)).


Los siguientes pasos **déjalos para el final**, para [la práctica final del coche](/salidas.md).

1. **CONECTAR LA RASPBERRY A LA WIFI Y ASIGNARLE UNA IP FIJA** [aquí cómo hacerlo](https://catedu.gitbooks.io/raspberry-muy-basico/content/4-primera-comunicacion.html) 
1. No obligatorio pero útil es el comunicarte vía remótamente de forma textual con SSH ([aquí](https://catedu.gitbooks.io/raspberry-muy-basico/content/5-ssh.html)) cambiar usuario y contraseña ([aquí](https://catedu.gitbooks.io/raspberry-muy-basico/content/6-cambiar-usuario-y-contrasena.html))
1. **CONECTARTE CON LA RASPBERRY de forma remota y gráfica con VNC** [aquí como hacerlo](https://catedu.gitbooks.io/raspberry-muy-basico/content/8-vnc.html) .

####Aclaraciones: ¿Necesito los 3 pasos anteriores para conectarme via remótamente con la Raspberry para la robótica Pibrella?

Podríamos usar la Raspberry con la Pibrella conectado con un teclado, ratón y una pantalla **y no necesitamos un ordenador, usamos el mismo ordenador que es la Raspberry!!**:

![](/assets/aparatos.png)

####PERO.. que pasaría si ...
Quieres hacer una práctica de la Pibrella donde se mueva por ejemplo [el coche](/salidas.md). Entonces estás obligado a comunicarte de forma remota.

**Para el resto de prácticas NO ES NECESARIO COMUNICARTE DE FORMA REMOTA** incluso es más rápido utilizar diréctamente la Raspberry con la Pibrella con pantalla, teclado y ratón.
 
# 2 CONFIGURAR SCRATCH para que utilice GPIO
En el Scractch de la RASPBERRY (ojo no de tu PC) tenemos que configurarlo para que interactúe con el GPIO de la Raspberry:

1. Hay que entrar en **SCRATCH 1.0** (ojo no la 2.0)
1. Editar - **Start GPIO server**

![](/assets/gpio-scratch.jpg)
>Para pararlo Editar - STOP GPIO Server

# 3 ¿CON SCRATCH 1.0??? ¿NO SE PUEDE CON SCRATCH 2.0?
Sí que se puede, pero como puedes ver en la siguiente presentación **SÓLO AÑADE 2 FUNCIONES** PARA LAS GPIO, con eso sí que se puede utilizar Pibrella **pero no tiene funciones específicas para Pibrella que sí que tiene Scratch 1.0**

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT-CzV7z9m4Zjgw-2Jo4g5oZJHz91PH4IcrHjbtcj0LF5HmkcdW35sWByiAMHOGAiX3cSRJhLBzfgk1/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

#4 ¿Y NO SE PUEDE CON PYTHON?
Pues sí, a[quí tienes las librerías](https://github.com/pimoroni/pibrella) que necesitas y ejemplos.


