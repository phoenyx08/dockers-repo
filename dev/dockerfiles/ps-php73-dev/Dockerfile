FROM php:7.3-fpm-alpine

RUN docker-php-ext-install mysqli \
  && docker-php-ext-install pdo_mysql \
  && apk add build-base \
  && pecl install xdebug-2.8.0 \
  && docker-php-ext-enable xdebug
