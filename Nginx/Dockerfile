FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install nginx -y zip curl

RUN echo "daemon off;" >> /etc/nginx/nginx.conf
RUN mv 2048/* /var/www/html/


EXPOSE 80
CMD [ "/usr/sbin/nginx" , "-c" , "/etc/nginx/nginx.conf"]
