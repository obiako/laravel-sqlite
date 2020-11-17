# Using SQLite in Laravel App

#### Introduction
You can use SQLite in your Laravel Application, it is easy to set up.


#### Step 1 - Change DB Connection in .env
Go to your .env file and change DB_CONNECTION from mysql to sqlite

FROM
```
DB_CONNECTION=mysql
```
TO 
```
DB_CONNECTION=sqlite
```

#### Step 2 - Delete DB_DATABASE from .env
By default, laravel locates the database.sqlite in database folder, delete the DB_DATABASE variable in .env

I usually just change the variable to something like this

```
qDB_DATABASE=laravel
```


#### Step 3 - Create database.sqlite
Go to database directory of your Laravel app

Create a file database.sqlite


#### You are good to go ! :rocket:


#### editing the sqlite file
You can download [Heidisql](https://www.heidisql.com/) and open the database.sqlite file. It is a powerful database client
