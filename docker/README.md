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

## Access the GUIs

- Grafana is available at http://\<DOCKER HOST\>:3000
- Chronograf (the InfluxDB UI) is available at http://\<DOCKER HOST\>:8888
- NodeRed is available at http://\<DOCKER HOST\>:1880 


(DOCKER HOST is 127.0.0.1 if you are using Docker Desktop or the IP address of the server running Docker Daemon)

Also, here are other ports for clients to connect to

- InfluxDB: <DOCKER HOST\>:8086 
- Mosquitto: <DOCKER HOST\>:1883 

## Stop the IoT platform Docker version

```console
docker$ docker-compose stop
````

## Remove the IoT platform Docker version


```console
docker$ docker-compose down -v
````
