# dockercompose_git

#Descripción#

services: A partir de aqui empiezan las declaraciones.

image: internetsystemsconsortium/bind9:9.16 Nombre de la imagen que se va a crear.

ports: Puertos que se van a utilizar.  - 7000:53/tcp  - 7000:53/udp

volumes: Volumenes que van a utilizar y asociados a las carpetas. 

volumes: Creación de los volumenes  configuration: options: secondaryzones: logfiles:
