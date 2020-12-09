# Documentation | Change Auth

## Change Auth of root
1. `sudo mysql`
2. `ALTER USER`
3. `'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';` Where 'password' - write your uniqe password, example: '123456he'
4. `exit` 

Recomended add MySQL user - [click](./add-mysql-user.md)