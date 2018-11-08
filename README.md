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

## Using Docker compose

Make sure you are in the same folder as `docker-compose.yaml` file.

1. Run docker compose configuration: `docker-compose up` (add `-d` flag to hide logs for each container) or `docker-compose up --build` if you need to build images
2. To stop and remove all containers/network: `docker-compose down`

If you have problems running `docker-compose up` command, check for any images related to this docker-compose and remove them by hand with `docker rmi`.