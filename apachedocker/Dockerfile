FROM phani99/docker-apache 
MAINTAINER  phani  <pk@domain.com>

RUN apt-get update && apt-get  install -y  apache2
RUN echo “Hello Apache server on Ubuntu Docker” > /var/www/html/index.html
EXPOSE 81
CMD /usr/sbin/apache2ctl -D FOREGROUND
