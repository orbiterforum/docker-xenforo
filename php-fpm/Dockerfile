# https://hub.docker.com/_/php/
FROM php:8.3-fpm-alpine3.20

ARG DOCKER_XENFORO_PHP_EXT_INSTALL="exif gd gmp mysqli opcache pcntl soap sockets zip"
ARG DOCKER_XENFORO_PHP_PECL_INSTALL="apcu igbinary memcached redis"

COPY . /tmp/.
RUN /tmp/build.sh
