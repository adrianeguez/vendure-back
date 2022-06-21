# vendure-back

## Error base de datos

```mysql
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY '{your password}';
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '{your password}';
SELECT plugin FROM mysql.user WHERE User = 'root';
```
