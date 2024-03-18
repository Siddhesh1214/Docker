FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install nginx -y 
COPY . .

RUN echo "daemon off;" >> /etc/nginx/nginx.conf
COPY 2048 /var/www/html/

EXPOSE 80
CMD [ "/usr/sbin/nginx" , "-c" , "/etc/nginx/nginx.conf"]
