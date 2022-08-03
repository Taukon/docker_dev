FROM php:7.4-apache 

COPY --from=composer /usr/bin/composer /usr/bin/composer

RUN apt-get update && apt-get install -y libonig-dev git libzip-dev unzip && \
    docker-php-ext-install pdo_mysql mysqli mbstring zip