# MANUAL-INSTALACIÓN-OWNCLOUD

 "sudo apt update"  sirve para actualizar la màquina

 Seguido del update, hacemos "sudo atp update", para subirlo a la maquina.

### Ahora despues de estos 2 pasos lo que vamos a hacer es una instalación del servidor de "apache2.

 Lo que haremos será lo siguiente "sudo apt install -y apache2" y lo instalaremos

Una vez hemos instalado el servidor web, lo siguiente que haremos será instalar la base de datos del servidor.

Para instalar esta base de datos pondremos "sudo apt install -y mysql-server"

### Como ultimos pasos para finalizar instalaremos un par de librerias "PHP"

1. sudo apt install -y php libapache2-mod-php

2. sudo apt install -y php-fpm php-common php-mbstring php-xmlrpc php-soap php-gd php-xml php-intl php-mysql php-cli php-ldap php-zip php-curl 

### Y para finalizar con la instalación, lo último que haremos será reiniciar el servidor de apache

 Realizando este comando: sudo systemctl restart apache2
