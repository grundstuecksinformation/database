# database

DDL from https://github.com/sogis/oereb-db

```
ILI2PG_PATH=/Users/stefan/apps/ili2pg-4.5.0/ili2pg-4.5.0.jar ./create_schema_sql_scripts.sh
```

```
mkdir -m 0777 ~/pgdata
docker run -p 54323:5432 -v ~/pgdata:/var/lib/postgresql/data:delegated -e POSTGRES_DB=oereb -e POSTGRES_PASSWORD=mysecretpassword edigonzales/postgis:13-3.1
```