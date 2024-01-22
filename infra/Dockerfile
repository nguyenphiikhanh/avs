#PHP 7.4
FROM php:7.4-apache

# WORKING DIRECTORY
WORKDIR /var/www/html

# COPY SRC TO /var/www/html/
COPY . .

# php extentions needed
RUN docker-php-ext-install mysqli pdo_mysql
RUN a2enmod rewrite

# Start Apache
CMD ["apache2-foreground"]