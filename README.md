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