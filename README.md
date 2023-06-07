# Todos API

- Endpoint : `/todos`
    - Supported operations : **GET**, **POST**, **PUT**, **DELETE**
  
## Compile, Test and Package

```shell
mvn package
```

## Push image to container registry

```shell
docker build -t todos-api:latest .
docker push todos-api:latest
```
