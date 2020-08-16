Debian-ISPConfig3-migration
===========================

Este script se utiliza para migrar datos de ISPConfig 3.

Este script está basado en el desarrollado por teris.

El script está basado en shell y se puede utilizar en cualquier servidor GNU de Ubuntu / Debian.
El script se probó en Debian Wheezy (7).

Tenga en cuenta que las contraseñas de usuario / grupos y UNIX deben insertarse manualmente.

Los datos de acceso se guardarán del servidor anterior. Se encuentra en el directorio / root / old-server /.
(passwd y grupo)

Los originales se pueden encontrar en / etc / passwd y / etc / group. Simplemente edítelos con un editor (vi o nano)

Ejemplo:

cat / root / old-server / passwd

Salida:

replicador: x: 1002: 1002: ,,,: / home / replicator: / bin / bash

Simplemente copie esto y guárdelo en el original:

nano / etc / passwd

root: x: 0: 0: root: / root: / bin / bash

replicador: x: 1000: 1000: ,,,: / home / replicator: / bin / bash

¡TERMINADO!


Descargar ...

Descomprimir ...

chmod 0777

¡empezar!
