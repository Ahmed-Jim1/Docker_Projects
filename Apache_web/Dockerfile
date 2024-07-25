FROM ubuntu:latest
RUN apt-get update && apt-get -y install apache2
EXPOSE 80
ENTRYPOINT ["apache2ctl", "-D" , "FOREGROUND"]

