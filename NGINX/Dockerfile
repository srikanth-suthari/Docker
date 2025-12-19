FROM nginx
RUN rm /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
EXPOSE 80
#We use this if we run nginx with other images
#To make the container alive and stable
#CMD ["nginx", "-g", "daemon off;"]
