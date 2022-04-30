FROM php:8-fpm

RUN pecl install xdebug-3.1.4 \
        && docker-php-ext-enable xdebug \
        && docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable mysqli pdo_mysql
