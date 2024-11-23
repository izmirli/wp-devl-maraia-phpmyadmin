# Docker compose setup for development of WordPress on LAMP

LAMP is: Linux, Apache, MariaDB & PHP.  
We also have phpMyAdmin for direct DB access.  

WordPress files will be under local `./wp-code` folder.  

Database docker volume will be created to save install & wp changes. After 1st run, delete volume if you want a fresh install.  

A local `.env` file is requierd. It should have these 4 parameters:

* MYSQL_ROOT_PASSWORD
* MYSQL_DATABASE
* MYSQL_USER
* MYSQL_PASSWORD

WordPress access by: http://localhost:8080/  
phpMyAdmin access by: http://localhost:8081/  
