￪ [bach to main](00_main.md)


# Direct PostgreSQL connection

port: 5432
host: localhost
database: mainnet

It is possible to directly connect to PostgreSQL:

```sh
psql -h localhost -p 5432 -U user12345 mainnet
```
(replace "user12345" with your assigned user name; this command will ask for the password)

_TODO_