FROM docksal/cli:php7.4-3.0

RUN apt-get update -y

RUN composer self-update --1

RUN apt-get install libgmp-dev -y

RUN docker-php-ext-install gmp

COPY php.ini /usr/local/etc/php/php.ini
