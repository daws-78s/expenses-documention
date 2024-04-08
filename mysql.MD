# MySQL

Developer has chosen the database MySQL. Hence, we are trying to install it up and configure it.

**Versions of the DB Software you will get context from the developer, Meaning we need to check with developer.**

Install MySQL Server 8.0.x

```
dnf install mysql-server -y
```

Start MySQL Service

```
systemctl enable mysqld
```
```
systemctl start mysqld
```

Next, We need to change the default root password in order to start using the database service. Use password ExpenseApp@1 or any other as per your choice.

```
mysql_secure_installation --set-root-pass ExpenseApp@1
```