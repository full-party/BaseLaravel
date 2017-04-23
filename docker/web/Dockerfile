FROM php:7.1-apache

# add web user
RUN useradd -m -s /bin/bash -u 1000 laravel

# install composer
RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer
