# docker-php
Para utilizarse con el comando `docker-compose`, construye 5 contenedores con:

* Nginx
* PHP-FPM
* MySQL
* PHPMyAdmin
* Composer

Con la idea de tener un ambiente de desarrollo para Drupal 8, que parte de un código ya existente, y que se puede administrar la base de datos con PHPMyAdmin, ejecutar comandos de composer, enrutar el contenido y peticiones por medio de Nginx y servir la versión más reciente de PHP (al día de hoy), con la mayor cantidad de librerias disponbles para que funcione bajo entornos tipo Linux con el stack antes mencionado.

Este proyecto hace uso de los siguientes puertos:

| Server     | Port |
|------------|------|
| MySQL      | 8989 |
| PHPMyAdmin | 8090 |
| Nginx      | 8000 |

El código debe ir en una carpeta a la par de `etc` con el nombre `code`. Este proyecto esta basado en el código de: [nanoninja/docker-nginx-php-mysql](https://github.com/nanoninja/docker-nginx-php-mysql)

Próximamente habrá más contenido, y detalle de su utilización...
