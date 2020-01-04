FROM php:7-fpm

RUN docker-php-ext-install mysqli && apt-get update && apt-get install -y python-pip git \
  && python -m pip install git+https://github.com/TheEnbyperor/python-brotherprint && apt-get purge -y python-pip git
