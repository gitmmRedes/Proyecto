FROM ubuntu:18.04
MAINTAINER http
RUN apt-get update
RUN apt-get -y install wget
RUN apt-get -y install unzip
RUN apt-get -y install apache2
RUN apt-get -y install bind9
RUN apt-get -y install nano
RUN wget https://github.com/gitmmRedes/ProyectoGit/archive/master.zip
RUN unzip /master.zip
RUN cp -a /ProyectoGit-master/* var/www/html
EXPOSE 80
CMD /usr/sbin/apache2ctl -D FOREGROUND 
