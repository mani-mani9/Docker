#/*FROM ubuntu
#LABEL maintainer="manikantapemmasani@gmail.com"
#RUN apt update && apt install tree -y
#COPY /Dev/index.html /var/www/html/index.html 
#WORKDIR /home
#VOLUME /demo
#EXPOSE 80

FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80

