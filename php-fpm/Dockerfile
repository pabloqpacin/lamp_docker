FROM php:8.1.27-fpm-bullseye

RUN docker-php-ext-install mysqli && \
    docker-php-ext-enable mysqli

# COPY src/ /var/www/html/

EXPOSE 80