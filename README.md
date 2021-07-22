# database

DDL from https://github.com/sogis/oereb-db

```
mkdir -m 0777 ~/pgdata
docker run -p 54323:5432 -v ~/pgdata:/var/lib/postgresql/data -e POSTGRES_DB=oereb -e POSTGRES_PASSWORD=mysecretpassword edigonzales/postgis:13-3.1
```