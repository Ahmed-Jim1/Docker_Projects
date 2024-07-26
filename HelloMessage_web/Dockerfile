FROM ubuntu

RUN apt-get update && apt-get install -y nginx

COPY app-code /var/www/html

EXPOSE 8080

CMD ["nginx","-g","deamon:off"]


