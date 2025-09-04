FROM php:7.4-apache

WORKDIR /var/www/html

COPY . .

EXPOSE 80

CMD ["apache2-foreground"]


# docker build -t basic_php . -> this is build command
# docker run -d -p 8080:80 basic_php -> this is run command