FROM ubuntu

RUN apt-get update && \ 
    apt-get clean && \ 
    rm -rf /var/lib/apt/lists/*

RUN apt-get install -y nginx

CMD ["nginx", "-g", "daemon off;"]

