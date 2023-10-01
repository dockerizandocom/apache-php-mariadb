# Apache PHP y MariaDB

Este proyecto crea un ambiente de desarrollo local con Linux, Apache, MySQL y PHP utilizando Docker Compose.

## Requisitos
Docker
Docker Compose
Levantar ambiente
git clone https://github.com/dockerizandocom/apache-php-mariadb
Levanta los contenedores:
docker-compose up -d

El servidor web estará disponible en http://localhost:8080

## Detalles
Apache está expuesto en el puerto 8080
MySQL expone el puerto 3306
PHPMyAdmin está disponible en http://localhost:8080/phpmyadmin
## Archivos
src: Directorio para los archivos PHP del proyecto
db: Base de datos MySQL y scripts SQL
logs: Logs de Apache y MySQL
docker-compose.yml: Definición de los servicios de Docker
## Credits
MariaDB
PHP
Apache
phpMyAdmin

Este README debe ayudarte a arrancar el ambiente LAMP con Docker Compose para desarrollo web. Puedes personalizarlo para tu proyecto específico.
