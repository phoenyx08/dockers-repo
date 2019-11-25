FROM php:7.3-fpm-alpine

RUN apk add build-base \
  && apk add autoconf \
  && apk add libxml2-dev \
  && pecl install xdebug-2.8.0 \
  && docker-php-ext-enable xdebug \
  && docker-php-ext-install mysqli \
  && docker-php-ext-install pdo_mysql \
  && docker-php-ext-install dom
