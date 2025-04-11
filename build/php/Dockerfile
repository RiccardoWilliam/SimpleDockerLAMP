FROM php:8.4-apache

# Installs PHP mysqli extension
RUN docker-php-ext-install mysqli

# Enabled Apache2 proxy module
RUN a2enmod proxy proxy_http 