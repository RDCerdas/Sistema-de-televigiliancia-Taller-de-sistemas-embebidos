Sistema de televigiliancia Taller de sistemas embebidos
 Proyecto 2 del curso taller de sistemas embebidos

Considerar los siguientes pasos para el uso del repositorio:

-Clonar poky dunfell: git clone -b dunfell git://git.yoctoproject.org/poky

 -Clonar el layer meta-raspberrypi: git clone -b dunfell git://git.yoctoproject.org/meta-raspberrypi

 -Clonar el meta openembedded: git clone https://github.com/openembedded/meta-openembedded.git

- Clonar el master de este repositorio en el mismo nivel que poky.

 Ejecutar en terminal al mismo nivel de poky: source poky/oe-init-build-env

Recordatorio: cambiar el archivo bblayer.bb con las direcciones correspondientes.
