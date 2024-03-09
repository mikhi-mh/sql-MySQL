# sql with MySQL

---

If you are using Windows, git bash and my-SQL server 8.0 ---

(make sure the path to MySQL is updated in Path in System Environment variables)
now you can open git bash to connect to my-sql server like this --->

```cmd
winpty mysql -u root -p
```
(here root is the username , then it will prompt to password)

---

mysql shell/ server will start

---


```mysql
show databases;
-- it will give list of all the databases present
```

---

```mysql
system cls; -- for windows to clear the o/p screen
system clear; -- for linux/mac to clear the o/p screen
```


statements/commands are case-insensitive

```mysql
CREATE DATABASE myDB;
CREATE DATABASE myDB2;
create dataBase myDb3;
cReate dataBase myDb4;
-- command statements/ keywords are case-insensitive
-- here db, schema, table names are case-insensitive
drop database mydb4;
create database mYdb4;
drop database mydb4;
create database mydb4;

use mydb4; 
-- set db to default

show databases;
-- show list of available databases

CREATE SCHEMA `tep5` ;
CREATE SCHEMA tep5 ;
--- create scheme and create database is same
CREATE DATABASE temp5;
```
