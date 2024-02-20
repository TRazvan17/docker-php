# docker-php
Docker - PHP


Pasi
1. Creare fisier docker-compose.yml
1.1. Rulare comanda razvan.taune@BUC158562994:/var/www/html/docker-php$ docker-compose up
2. Creare DockerFile php -> Dockerfile
2.1. Rulare comanda razvan.taune@BUC158562994:/var/www/html/docker-php$ docker build -t test:php81 -f php/Dockerfile .
2.2. Verificare creare container
   razvan.taune@BUC158562994:/var/www/html/docker-php$ docker images
   REPOSITORY   TAG              IMAGE ID       CREATED              SIZE
   test         php81            7f2e193c2376   About a minute ago   78.3MB
   nginx        latest           e4720093a3c1   5 days ago           187MB
   php          8.1-fpm-alpine   8243e16a172d   3 weeks ago          78MB
3. Configurare Nginx

