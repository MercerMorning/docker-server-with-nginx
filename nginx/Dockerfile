FROM nginx

RUN apt-get update && apt-get install nano

ADD vhost.conf /etc/nginx/conf.d/default.conf
ADD nginx.conf /etc/nginx/nginx.conf

WORKDIR /var/www/html