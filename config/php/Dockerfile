FROM php:5.6-fpm

#RUN docker-php-ext-install pdo pdo_mysql
RUN apk add --no-cache git bash tini memcached php5-pcntl php5-common php5-openssl php5-json php5-phar php5-zlib php5-xml php5-curl php5-dom php5-pdo php5-memcache php5-mysql php5-pdo_mysql \
        && docker-php-ext-install pcntl pdo_mysql mysql json \
        && docker-php-ext-enable pcntl pdo_mysql mysql json