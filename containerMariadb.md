## Create a MariaDB Container With Docker
 
   `sudo docker pull mariadb`
 
 
  `sudo docker run --restart always -d --name mariadb -p 3306:3306 -e MYSQL_ROOT_PASSWORD=mariadb mariadb`
  

