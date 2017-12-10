FROM php:7.2.0-fpm

ADD ./php.ini /usr/local/etc/php/php.ini
ADD ./php-fpm.conf /usr/local/etc/php-fpm.conf
ADD ./php-fpm.d/ /usr/local/etc/php-fpm.d

RUN sed -i "s/;date.timezone =/date.timezone = Asia\/Tokyo/" /usr/local/etc/php/php.ini

ADD app/ /app
