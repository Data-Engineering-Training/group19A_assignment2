# group19A_assignment2

Contributors - GROUP 19A
-------------------------
1. Daniel Dake

Requirements:
-------------
docker >= 17.12.0+ docker-compose

Quick Start
-------------
Clone or download this repository
Go inside of directory, cd group19A_assignment2
Run the command "docker-compose up -d"


YML Environment variables:
--------------------------
MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=northwind_db
MYSQL_USER=mysql

MONGO_INITDB_ROOT_USERNAME=admin
MONGO_INITDB_ROOT_PASSWORD=admin123
MONGO_INITDB_DATABASE=northwind_db

Access to mysql:
-----------------
localhost:3306
Username: mysqluser
Password: root

Access to MongoDB:
------------------
localhost=27017
Username=admin
Password=admin123

Access to phpmyadmin (A web interface for MySQL)
-------------------------------------------------
PMA_HOST=mysql
PMA_PORT=8081
MYSQL_ROOT_PASSWORD=root