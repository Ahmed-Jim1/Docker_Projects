FROM ubuntu

RUN apt-get update && \ 
    apt-get install -y nginx

COPY app-code /usr/share/nginx/html/

EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]


