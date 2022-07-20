# Lamp Docker Image
 Simple docker image for lamp setup.
 All php files or webpages should be placed on www/html/ folder.
## Webserver
    Image:php:7.4.2-apache-buster
## PhpmyAdmin
    Image: phpmyadmin/phpmyadmin:5.0.1
    HOST: mysql-server
    USER: root
    PASSWORD: secret
    ports:5000:

## mysql
    Image: mysql:8.0.19

## Install Docker
 Download docker from official page if not installed [https://docs.docker.com/get-docker/].

## Create lamp docker image
 - Clone the repository by running this command `git clone https://github.com/moithaopi/Lamp-docker.git` .
 - Then move into the root folder of Lamp-docker using this command `cd Lamp-docker`.
 - Run this command `docker-compose up -d` for docker to pull images from docker repository into your local machine and create lamp-image
 - Check if the lamp docker images is running by using this command `docker ps`

