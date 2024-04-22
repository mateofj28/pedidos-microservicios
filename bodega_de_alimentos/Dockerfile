FROM php:8.0-alpine

WORKDIR /app

RUN git clone https://github.com/laravel/laravel .
RUN composer install

# Configuración adicional del proyecto Laravel (si es necesario)

CMD ["php", "artisan", "serve"]
