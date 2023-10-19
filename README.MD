## Import SQL file sql.gz 

```bash
gzip -d myfile.sql.gz | mysql -u root -p database_name


## Import SQL file sql.gz (mysql sail)

```bash
gzip -d myfile.sql.gz | sail mysql -u root -p database_name
