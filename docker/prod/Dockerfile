FROM composer:2 AS vendor

WORKDIR /symfony

COPY ../../symfony/composer.json ../../symfony/composer.lock ../../symfony/symfony.lock ./

RUN composer install --no-dev --no-scripts --prefer-dist --optimize-autoloader
