FROM composer:latest
WORKDIR /app
RUN composer global require laravel/installer
COPY . /app 
EXPOSE 8000
CMD php artisan serve --host 0.0.0.0
