# dockercompose_git

#Descripción#

services: A partir de aqui empiezan las declaraciones.

image: internetsystemsconsortium/bind9:9.16 Nombre de la imagen que se va a crear.

ports: Puertos que se van a utilizar. En nustro caso "5353:53".

volumes: Volumenes que van a utilizar y asociados a las carpetas. etc:/etc/bind cache:/var/cache/bind lib:/var/lib/bind log:/var/log

volumes: Creación de los volumenes etc: cache: lib: log:
