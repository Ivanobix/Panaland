# Panaland
Servidor de Minecraft Survival 1.16.5 con plugins y totalmente configurado.

## Descripción general

Panaland se trata de un servidor de Minecraft (1.16.5) orientado a la modalidad survival (multijugador) y por tanto no está diseñado para soportar grandes cantidades de jugadores conectados simultáneamente (20 personas sería lo ideal).

Se ha buscado obtener el máximo rendimiento posible para que el servidor pueda ser hosteado desde dispositivos con bajos recursos, como una Raspberry Pi 4 Model B de 4GB.

Para esto se han ajustado cuidadosamente todos los archivos de configuración y se han instalado determinados plugins orientados a la mejora del rendimiento.
También se han incluido plugins de control de usuarios, economía, mochilas, mobs personalizados, etc y un mapa custom inmenso, permitiendo una experiencia más completa e infinitamente más atractiva que la que ofrece el juego base.

## Instalación

Dado que el servidor ha sido configurado con la versión 11 de Java, se requiere como mínimo que dicha versión esté instalada el equipo que hará las veces de servidor, pudiendo ser sustituida por una versión más reciente, como la 1.16, pero no se asegura su compatibilidad.

## Puesta en marcha

Dado que ya todo se encuentra configurado, solo tendremos que clonar este repositorio y ejecutar el servidor:
  - Windows:
      - Nos dirigimos al directorio donde hayamos clonado el repositorio y ejecutar el archivo "run.cmd" como administrador.
  - Linux:
      - Nos dirigimos al directorio donde hayamos clonado el repositorio y mediante la consola ejecutamos el archivo run.sh (Mediante el comando "sudo bash run.sh")

Una vez hayamos hecho esto, el servidor comenzará a cargar todo lo necesario, lo cual llevará un par de minutos o más dependiendo de las características del equipo que lo ejecute, pero ojo, no existe ningún mensaje que indique que el servidor ya se ha terminado de cargar, así que debes guiarte en función de si siguen apareciendo nuevos mensajes en el terminal.

Importante:
Si quieres detener el servidor, es muy importante que no cierres la consola directamente, dado que esto podría romper el servidor, por lo que deberás utilizar el comando "stop" directamente desde la consola. De esta forma todos los datos se guardarán y el servidor se cerrará de forma segura.

## Manual de uso

Una vez el servidor esté iniciado no es necesario hacer nada más, ya es totalmente jugable, pero si te sientes con ganas de investigar, verás que existen un millón de posibilidades para mejorar tu servidor, así que te animo a que no te conformes con lo que acabas de conseguir y sigas añadiéndole cosas, quién sabe si a la larga tu pequeño servidor se convertirá en un referente dentro del mundo de Minecraft.

### Como conectarte

Para conectarte desde tu red local basta con añadir el servidor en Minecraft indicando que la dirección es "localhost", pero si lo que quieres es que tus amigos puedan conectarse desde su casa, necesitarás configurar tu router para que apunte a tu servidor.

Por desgracia esto varía mucho de unos routers a otros, así que no puedo dejar una guía sobre como hacerlo, pero existen miles de tutoriales en YouTube que te lo explican paso a paso, así que no te preocupes, suele ser extremadamente sencillo.

### Ajuste de rendimiento

Por defecto el servidor está configurado para que consuma 2GB de RAM en la máquina que lo ejecuta, pero si tu equipo es lo suficientemente potente, puedes aumentar dicha cifra, lo que permitirá que tu servidor funcione aún mejor.

Para cambiar esto basta con acceder al archivo de arranque (run.cmd en el caso de Windows o run.sh en Linux) y modificar las propiedades:
  - Xmx2G (RAM máxima)
  - Xms2G (RAM mínima)

Ah, y no te recomiendo que pongas menos de 2GB ni que el servidor consuma más del 50% de tu memoria RAM disponible.

### Actualizaciones

Durante el inicio del servidor es probable que aparezcan mensajes de que existen actualizaciones disponibles para determinados plugins, esto es algo totalmente normal.

Me he asegurado de que todos los que están incluidos actualmente se tratan de versiones estables y no debería ser necesario actualizar ninguno, pero si aún así quieres tener lo último cada vez que salga una actualización, puedes actualizarlos siguiendo las instrucciones que te indican en la propia consola, aunque eso sí, asegurate de detener antes el servidor y hacer una copia de seguridad por si algo saliese mal.

## Información adicional:

En caso de que cualquier persona desee eliminar algún plugin así como modificar los mapas, basta con eliminarlos y sustituirlos directamente, sin más complicaciones.

De igual forma, el resto de configuraciones son totalmente personalizables, por lo que sentiros libres de experimentar cosas nuevas.

## Ayuda

[Ayuda](https://github.com/Ivanobix/Panaland/issues)

## Créditos

[Mapa Custom Overworld](https://www.planetminecraft.com/project/drehmal-v2-prim-rdial-12k-x-12k-survival-adventure-map/)

## Licencia

[Resumen](https://creativecommons.org/licenses/by-nc/4.0/deed.es)

[Texto Legal](https://creativecommons.org/licenses/by-nc/4.0/legalcode.es)
