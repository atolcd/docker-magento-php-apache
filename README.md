# Magento 1.6 Docker Image

## Why PHP 5.3 ?

There is no more PHP 5.3 official Docker Image. As Magento 1.6 still need this old PHP version we made a Docker image for developpment purpose.

This image include PHP + Apache, and all PHP extension needed by Magento (Curl, Dom, GD, Hash, iconv, mcrypt, pcre, pdo, pdo_mysql, simplexml) + Xdebug to simplify development process.

## How to use ?

Just use this image in addition to a MySQL image (in a docker-compose for example).

## Inspiration

https://github.com/cristianorsolin/docker-php-5.3-apache