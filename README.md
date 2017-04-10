# Instalar Ubuntu Desktop 16.04 sobre VirtualBox

## Descargar imagen de Ubuntu 16.04

El tutorial está hecho con la versión de Ubuntu 16.04.2. Descargar la imagen ISO de la siguiente dirección:

* [https://www.ubuntu.com/download/desktop](https://www.ubuntu.com/download/desktop)

## Creación de la Máquina Virtual

Abrir el VirtualBox y crear una nueva máquina virtual pulsando en el botón _Nueva_:

![img01](/images/01_config_vbox/img01.png)

Configuramos el nombre de la máquina virtual:

* **Nombre**: Ubuntu16
* **Tipo**: Linux
* **Versión**: Ubuntu (64 bits)

![img02](/images/01_config_vbox/img02.png)

Configurar la cantidad de memoria RAM que se le va a asignar, en este caso, 1,5GB=1536MB (depende de la cantidad de memoria RAM de nuestor ordenador, para ordenadores con pocos recursos asignar 1GB de memoria RAM):

![img03](/images/01_config_vbox/img03.png)

Creamos el disco duro virtual:

![img04](/images/01_config_vbox/img04.png)

Elegimos el tipo de disco duro _VDI_, tal y como viene por defecto:

![img05](/images/01_config_vbox/img05.png)

Marcar la opción _Reservado dinámicamente_, esto significa que el disco que acabamos de crear crecerá a medida que se vaya llenando:

![img06](/images/01_config_vbox/img06.png)

Seleccionar el nombre del disco duro, en este caso dejamos el valor por defecto (coincide con el nombre de la máquina virtual) y asignar 16GB de tamaño al disco y pulsamos en **Crear**:

![img07](/images/01_config_vbox/img07.png)

## Montar la imagen de Ubuntu 16.04 en la Unidad de CD-ROM virtual de la máquina virtual:

Seleccionar la máquina virtual que acabamos de crear y pulsar en la opción configuración.

![img08](/images/01_config_vbox/img08.png)

En _Almacenamiento_, seleccionar el icono del CD-ROM vacío para configurar la unidad de CD-ROM virtual:

![img09](/images/01_config_vbox/img09.png)

Pulsamos sobre el icono del CD-ROM:

![img10](/images/01_config_vbox/img10.png)

Pulsar en el menú desplegable la opción _Seleccione archivo de disco óptico virtual..._:

![img11](/images/01_config_vbox/img11.png)

Navegar por el sistema de ficheros y seleccionar la imagen descargada de Ubuntu 16.04 previamente:

![img12](/images/01_config_vbox/img12.png)

Ahora en unidad de CD-ROM virtual aparece la imagen de Ubuntu 16.04 montada:

![img13](/images/01_config_vbox/img13.png)

En la pestaña **Sistema** seleccionar la etiqueta _Procesador_ para configurar el número de CPUs que vamos a asignar a la máquina virtual:

![img14](/images/01_config_vbox/img14.png)

Seleccionamos 2 CPU y pulsamos **OK** (esto depende del número de CPUs que tenga nuestro ordenador, para ordenadores con pocos recursos, asignar 1 CPU):

![img15](/images/01_config_vbox/img15.png)


## Instalar Ubuntu 16.04

Iniciar la máquina virtual Ubuntu16 que creamos anteriormente:

![img01](/images/02_install_ubuntu/img01.png)

Seleccionamos _Español_ en el menú de la izquierda y pulsar sobre la opción **Instalar Ubuntu**:

![img02](/images/02_install_ubuntu/img02.png)

Dejar las opciones que vienen en esta pantalla desmarcadas, tal y como viene por defecto, y pulsar **Continuar**:

![img03](/images/02_install_ubuntu/img03.png)

Dejar la opción marcada **Borrar disco e instalar Ubuntu**, tal y como viene por defecto y pulsar **Instalar Ahora**:

![img04](/images/02_install_ubuntu/img04.png)

Se muestra un mensaje de que los datos que tengamos en el disco virtual se van a borrar y pulsar **Continuar**:

![img05](/images/02_install_ubuntu/img05.png)

Seleccionar la zona horaria **Canary**, pulsar **Continuar**:

![img06](/images/02_install_ubuntu/img06.png)

Configurar la disposición del teclado a **Español** y pulsar **Continuar**:

![img07](/images/02_install_ubuntu/img07.png)

Crear el usuario del sistema y asignarle una contraseña:

![img08](/images/02_install_ubuntu/img08.png)

¡Listo! La instalación se ha realizado con éxito, pulsar **Reiniciar ahora** para reiniciar la máquina virtual:

![img09](/images/02_install_ubuntu/img09.png)

Antes de reiniciar, nos pide pulsar la tecla ENTER para eliminar la imagen de Ubuntu del CD-ROM virtual, así que pulsamos la tecla **ENTER**:

![img10](/images/02_install_ubuntu/img10.png)

## Configurar el Teclado a Español

Si durante el proceso de instalación, hemos instalado el teclado en Inglés y no en Español, para cambiarlo debemos seguir los siguientes pasos:

Pulsar en el icono **En** que aparece en la barra de tareas de Ubuntu. Este icono indica la distribución de teclado que estamos usando, en este caso el inglés:

![img01](/images/03_config_keyboard/img01.png)

Pulsar en la opción **Text Entry Settings..." del menú desplegable:

![img02](/images/03_config_keyboard/img02.png)

Pulsar en el icono **+** para añadir una nueva distribución de teclado:

![img03](/images/03_config_keyboard/img03.png)

Seleccionar el teclado **spanish** y pulsar **Add**. Esto nos añadirá la distribución de teclado en español:

![img04](/images/03_config_keyboard/img04.png)

Ahora tenemos que indicar que la distribución de teclado en español sea la distribución por defecto, para ello, seleccionar el teclado **Spanish** y pulsar la flecha hacia arriba para mover la distribución de teclado en español por delante de la distribución de teclado en inglés:

![img05](/images/03_config_keyboard/img05.png)

Ahora la distribución de teclado en español debería aparecer el primero antes que la distribución de teclado en inglés y cerrar la ventana:

![img06](/images/03_config_keyboard/img06.png)

Pulsar en el icono **En** que aparece en la barra de tareas de Ubuntu:

![img07](/images/03_config_keyboard/img07.png)

En el menú desplegable, seleccionar ahora la distribución de teclado en español (Es):

![img08](/images/03_config_keyboard/img08.png)

Ahora en la barra de tareas vemos que tenemos activado la distribución de teclado en Español (Es):

![img09](/images/03_config_keyboard/img09.png)



