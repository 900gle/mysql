mysql


docker exec -it mysql bash

mysql -uroot -p --port 3306

:root

ALTER USER 'root'@'localhost' IDENTIFIED BY 'doo';

flush privileges;


mysql> show databases;
create database shop;

mysql> create user ldh; 

ALTER USER 'ldh'@'%' IDENTIFIED BY 'doo';

flush privileges;

GRANT ALL PRIVILEGES ON *.* TO ldh@'%';
