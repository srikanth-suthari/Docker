FROM ubuntu
#using ubuntu os as base image
RUN apt update && apt upgrade -y
#installing apache2 into this ubuntu image
RUN apt install apache2 -y
RUN rm /var/www/html/index.html
#copying the new index.html file into the html dir
COPY index.html /var/www/html/
#running the apache service in foreground with this cmd
CMD ["apache2ctl", "-D", "FOREGROUND"]

