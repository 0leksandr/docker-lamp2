FROM php:7.4.0-fpm-alpine3.10
RUN apk update; \
    apk upgrade;
RUN docker-php-ext-install pdo pdo_mysql mysqli
