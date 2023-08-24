# Snippet Box

## Creating a local database

```console
docker run --name mysql01 -e MYSQL_ROOT_PASSWORD=A@12345678 -e MYSQL_DATABASE=snippetbox -e MYSQL_USER=sb-admin -e MYSQL_PASSWORD=Sb@12345678 -p 3306:3306 -d mysql:8.0.34
```
