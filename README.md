Bu proje MLOPS BOOTCAMP 15. projenin örnegidir.

## 1. Open mysql database

## 2. Connect to the database

```
docker exec -it mlflow_db mysql -u root -p
```

## 3. Show database and tables

```
mysql> show databases;
```

```
mysql> use mlops;
```

```
mysql> show tables;
```

```
mysql> select user from mysql.user;
```

```
mysql> exit
```

## 4. Connect to database

```
docker exec -it mlflow_db bash
```

```
mysql -u mlops_user -D mlops -p
```

```
truncate table hepsiburada;
```

```
mysql> select * from hepsiburada;
```




