FROM php:7.3-fpm

# 安装必要的 php 插件
RUN apt-get update && apt-get install -y \
    && docker-php-ext-install pdo_mysql && docker-php-ext-enable pdo_mysql \
    && docker-php-ext-install mysqli && docker-php-ext-enable mysqli
