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

Stop the container :  
    `docker-compose stop`  

List containers :  
    `docker-compose ps`  
this command is for display all the current container who runs on the current project.

List container logs :  
    `docker-container logs -f`  

Tail the container's logs  :  
    `docker-container logs -f [service]`  
Replace [service] with a service name (e.g. nginx) to display this service's logs only.

Restart the container :  
    `docker-compose restart`  

Stop and/or Destroy container:  
    `docker-compose down`  

Stop and/or destroy the containers and their volumes  
    `docker-compose down -v`  

Delete everything, including images and orphan containers  
    `docker-compose down -v --rmi all --remove-ophans`  

