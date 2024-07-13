FROM php:7.4-apache

# Instalar extensiones PHP y herramientas necesarias
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Copiar el código de la aplicación
COPY ./index.php /var/www/html/

