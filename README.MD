
## Import Sql file .sql
```bash
mysql -p -u user_name data_base < db_backup.sql
```

## Import Sql file .sql (mysql sail)
```bash
sail mysql -p -u user_name data_base < db_backup.sql
```

## Import SQL file sql.gz 

```bash
gzip -d myfile.sql.gz | mysql -u root -p database_name
```

## Import SQL file sql.gz (mysql sail)

### step 1
```bash
gzip -d myfile.sql.gz
```
### step 2
```bash
sail mysql -p -u user_name database_name < myfile.sql
```

## problem import sql

if table is LOCK when opening table. you can running ``UNLOCK TABLES`` on sql editor 
