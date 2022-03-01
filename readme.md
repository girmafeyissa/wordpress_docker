## Wordpress, MySQL , PHPMyAdmin  in Docker

this is a Boilerplate to setup wordpress in docker

wordpress is accessed on port 8000 (http://localhost:8000)

phpmyadmin is accessed on port 8001 (http://localhost:8001)



### mysql
- MYSQL_ROOT_PASSWORD=root

- MYSQL_DATABASE=wordpress_docker
      
- MYSQL_USER=wordpress

- MYSQL_PASSWORD=wordpress



run docker-compose up -d to install the images