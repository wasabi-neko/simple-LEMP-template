FROM php:7.1-fpm

RUN apt-get update
# RUN apt-get install -y iputils-ping
# RUN docker-php-ext-install mysqli
# RUN docker-php-ext-enable mysqli
RUN docker-php-ext-install pdo pdo_mysql
RUN docker-php-ext-enable pdo pdo_mysql