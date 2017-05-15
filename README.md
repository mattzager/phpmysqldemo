# phpmysqldemo

Add MySQL pod


Add environment variables to match your MySQL pod, e.g.

MYSQL_SERVICE_HOST=mysql

MYSQL_SERVICE_PORT=3306

MYSQL_SERVICE_DATABASE=phpmysqldemo

MYSQL_SERVICE_USERNAME=phpmysqldemo

MYSQL_SERVICE_PASSWORD=phpmysqldemo


Open terminal in MySQL pod and verify data, e.g.

mysql --host=127.0.0.1 --user=phpmysqldemo --password=phpmysqldemo phpmysqldemo

mysql> show tables;

mysql> select * from visitors;
