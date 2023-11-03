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
