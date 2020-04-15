FROM ubuntu:16.04

RUN apt-get update

RUN  apt-get install apache2 -y 

COPY amit.html /var/www/html/info.html

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
