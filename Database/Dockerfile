FROM mysql:latest


LABEL App="Sudent-App"
LABEL App_engg="Siddhesh"

RUN yum install httpd -y
COPY index.html /var/www/html/index.html

EXPOSE 80
CMD httpd -DFOREGROUND