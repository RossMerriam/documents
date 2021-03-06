# MySQL/Maria DB Commands

Below is a list of commonly used MariaDB and MySQL commands.

**‌Create a new database:**
`MariaDB> create database DATABASE_NAME;`

**Create a new user with only local access and grant privileges to this user on a database**
`MariaDB> grant all privileges on DATABASE_NAME.* TO 'USER_NAME'@'localhost' identified by 'PASSWORD';`

**Flush Privileges**
`MariaDB> flush privileges;`

**Show All Users**
`SELECT User from mysql.user;`

**Change User Password**
`ALTER USER 'USER_NAME@'localhost' IDENTIFIED BY 'mariadb';`

**Delete User**
`DROP USER 'USER_NAME'@'localhost';