# SkipRope
Music streaming service

## Shema [(xml)](./doc/shema.xml)  
![shema](./images/shema.png)

## Database (postgres)

1. Running docker image: `docker run --name skiprope-postgres -e POSTGRES_PASSWORD=skiprope --publish 5432:5432 -d postgres`

## Configuration management

1. Running consul docker image: `docker run -d --name=dev-consul --net=host consul`
