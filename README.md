# docker_lamp
Le nécessaire pour créer votre LAMP docker avec :
* Apache et PHP 5.6 
* Mysql 5.5
* Phpmyadmin 4.4.9

Dans le répertoire de votre choix :

$> git clone https://github.com/frlaugier/docker_lamp.git

$> cd docker_lamp

$> docker-compose run -d

Apache accessible en http://localhost

Phpmyadmin en http://localhost:8080

User : root

passwd : password

Les fichiers web sont accessibles dans docker_lamp/public_html

Les fichiers BD dans docker_lamp/mysql
