FROM ubuntu
RUN apt update && apt upgrade -y
RUN apt install apache2 -y
RUN rm /var/www/html/index.html
COPY index.html /var/www/html/
CMD ["apache2ctl", "-D", "FOREGROUND"]