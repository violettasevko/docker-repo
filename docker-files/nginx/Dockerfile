    FROM ubuntu:22.04
    LABEL maintainer="Vio"
    RUN apt-get update && apt-get upgrade -y
    RUN apt-get install nginx -y
    EXPOSE 80 443
    VOLUME /usr/share/nginx/html 
    CMD ["nginx", "-g", "deamon off"]
