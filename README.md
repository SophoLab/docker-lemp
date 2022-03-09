# Docker

 - Reference
    [The lemp stack tutorial article](https://tech.osteel.me/posts/docker-for-local-web-development-part-1-a-basic-lemp-stack)
    [Dockerhub nginx official repository](https://hub.docker.com/_/nginx)
    [Dockerhub php official repository](https://hub.docker.com/_/php)
    [Make PHP-FPM work with NGINX configuration](https://www.linode.com/docs/guides/serve-php-php-fpm-and-nginx/)


 - Great docker-compose commands 

For run docker compose container :   
    `docker-compose up -d`  

The `docker compose up` run the container and `-d` is for run the process in background.

For stop container :  
    `docker-compose stop`  

For see all container on the current project :  
    `docker-compose ps`  
this command is for display all the current container who runs on the current project.

For see container logs :  
    `docker-container logs -f`  

for see logs of one service only type : 
    `docker-container logs -f name_of_the_service`