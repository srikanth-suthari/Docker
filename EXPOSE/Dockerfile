FROM almalinux:9
RUN dnf install nginx -y
#this works only as an instruction to the user on which port the container has to be run
EXPOSE 80
CMD ["nginx","-g","daemon off";]