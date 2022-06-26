FROM ubuntu:22.10

RUN \
    apt update && \
    apt install -y net-tools && \
    apt install -y curl && \
    apt install -y nginx && \
    echo "\ndaemon off;" >> /etc/nginx/nginx.conf && \
    chown -R www-data:www-data /var/lib/nginx

COPY myindex.html /var/www/html
COPY myindex2.html /var/www/html

WORKDIR /etc/nginx

CMD ["nginx"]

EXPOSE 80