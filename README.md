# ComunicacionesEspeculativas
Bacterial AI machine


**Instalación netatalk**


1- Installation:

> sudo apt-get update

>sudo apt-get install netatalk

2- Configuration

**Stop the service:**

>sudo /etc/init.d/netatalk stop

**Open the configuration file:**

>sudo nano /etc/netatalk/AppleVolumes.default

**You can edit the mount folder if you wish or leave the default value:**

>~/ "Home Directory"

**Start the service again**

>sudo /etc/init.d/netatalk start
