FROM php:7.3.3-apache
RUN apt-get --allow-unauthenticated update && apt-get --allow-unauthenticated upgrade -y
RUN docker-php-ext-install mysqli
EXPOSE 80
