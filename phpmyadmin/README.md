Run this after mysql container is up and running

```
docker exec -it mysql_db mysql -u root -p -e "GRANT ALL PRIVILEGES ON *.* TO 'admin'@'%' WITH GRANT OPTION; FLUSH PRIVILEGES;"   
```
