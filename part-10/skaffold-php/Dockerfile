FROM php:7-cli-alpine AS development

RUN apk add --update git

RUN mkdir /app && chown www-data:www-data /app

USER www-data
WORKDIR /app

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

COPY --chown=www-data:www-data ./composer.json /app/composer.json

RUN composer install

COPY --chown=www-data:www-data . /app

ENTRYPOINT [ "php" ]
CMD [ "-S", "0.0.0.0:8080", "-t", "public", "public/index.php" ]
