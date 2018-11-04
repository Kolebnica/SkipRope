# SkipRope
Music streaming service

## Shema [(xml)](./doc/shema.xml)  
![shema](./images/shema.png)

## Database (postgres)

1. Running docker image: `docker run --name skiprope-postgres -e POSTGRES_PASSWORD=skiprope --publish 5432:5432 -d postgres`

## Configuration management

1. Running consul docker image: `docker run -d --name=dev-consul --net=host consul`

## Maven project structure
Predpisana in zaželjena [struktura](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html?fbclid=IwAR2Ix3y_8HpP4bFjVu_q2gp5_elbSmJKJgaJ9FdgfmBBvTBcwtTEsWpRtJo) maven projekta.
