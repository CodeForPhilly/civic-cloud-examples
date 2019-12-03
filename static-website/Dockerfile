FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install -y nginx

COPY . /var/www/html

ENTRYPOINT [ "nginx", "-g", "daemon off;" ]
