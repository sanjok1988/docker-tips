# docker-tips


docker-compose up -d nginx mysql phpmyadmin
docker exec -it laradock_workspace_1 bash
docker exec -it laradock_mysql_1 bash


http://localhost:8080/index.php


mysql -u root -p
root
alter user 'root'@'localhost' identified with mysql_native_password by 'password';

ALTER USER 'default' IDENTIFIED WITH mysql_native_password BY 'secret';

server = mysql
user = default
password = secret
