# Documentation | Add MySQL user

## Add MySQL user
1. `mysql -u root -p`
2. `CREATE USER 'unique_user'@'localhost' IDENTIFIED BY 'password';` - where 'unique_user' - name of your new unique user, 'password' - unique password of your new user.
3. `GRANT ALL PRIVILEGES ON *.* TO 'user'@'localhost' WITH GRANT OPTION;` where 'user' - name of your new user
4. `exit`