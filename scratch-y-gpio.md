#1 CONFIGURAR TU RASBERRY
###1.1 Instalar el Sistema Operativo en la Rasbperry
Tienes que instalar el sistema operativo Raspbian en la micro tarjeta SD (que ya tiene **Python**) para ello tienes que seguir los pasos de los apuntes de [**los apuntes Raspberry muy básico**](https://catedu.gitbooks.io/raspberry-muy-basico/content/). Concrétamente el [capítulo 3](https://catedu.gitbooks.io/raspberry-muy-basico/content/3-raspbian.html).

###1.2 COMUNICARNOS CON LA RASPBERRY
####1.2.1 Opción A NO REMOTO
Podríamos usar la Raspberry conectado con un teclado, ratón y una pantalla **y no necesitamos un ordenador, usamos el mismo ordenador que es la Raspberry!!**:

![](/assets/aparatos.png)

####1.2.2 Opción B REMOTO
Podemos trabajar cómodamente en nuestro ordenador, y entrar en la Raspberry vía wifi. De los anteriores aparatos: sólo necesitamos la alimentación:

1. Una vez instalado Raspbian tienes que conectar la Raspberry a la wifi, para ello sigue los pasos marcados en el [capítulo 4](https://catedu.gitbooks.io/raspberry-muy-basico/content/4-primera-comunicacion.html).
1. Recomendable pero no obligatorio, es aprender a configurar el sistema operativo, [comunicarte con él via texto por SSH](https://catedu.gitbooks.io/raspberry-muy-basico/content/5-ssh.html), [cambiar el usuario, contraseña](https://catedu.gitbooks.io/raspberry-muy-basico/content/6-cambiar-usuario-y-contrasena.html), esto sí que es obligatorio: [tienes que aprender a apagar](https://catedu.gitbooks.io/raspberry-muy-basico/content/7-apagar.html) ;).
1. Luego tienes que comunicarte en este curso VIA GRÁFICAMENTE por VNC lo tienes explicado en [el capítulo 8](https://catedu.gitbooks.io/raspberry-muy-basico/content/8-vnc.html).

####1.2.3 ¿Qué opción elegimos?
Nosotros la B, porque si queremos hacer un coche, entonces, no tenemos otro remedio.
 
# 2 CONFIGURAR SCRATCH para que utilice GPIO
En el Scractch de la RASPBERRY (ojo no de tu PC) tenemos que configurarlo para que interactúe con el GPIO de la Raspberry:

1. Hay que entrar en **SCRATCH 1.0** (ojo no la 2.0)
1. Editar - **Start GPIO server**

![](/assets/gpio-scratch.jpg)
>Para pararlo Editar - STOP GPIO Server


