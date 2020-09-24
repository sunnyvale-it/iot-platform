# Install IoT platform using Docker

## Prerequisites

Having installed:

- Docker (Desktop or Toolbox)
- Docker Compose

## Run the IoT platform Docker version

1) Modify the **.env** file according to your needs

```console
docker$ vi .env
...
````

2) Start the containers

```console
docker$ docker-compose up
````

## Stop the IoT platform Docker version

```console
docker$ docker-compose stop
````

## Remove the IoT platform Docker version


```console
docker$ docker-compose down -v
````
