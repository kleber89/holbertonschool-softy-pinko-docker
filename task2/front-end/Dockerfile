FROM nginx:latest

RUN apt-get update && apt-get install -y nginx

COPY softy-pinko-front-end file/var/www/html/softy-pinko-front-end

COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 9000
