# Use the official image as a parent image.
FROM php:7.4-fpm

# Run the commands inside your image filesystem.
RUN apt-get update
RUN apt-get install nano
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install mysqli
RUN docker-php-ext-install bcmath 
