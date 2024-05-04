# ELK STACK USING DOCKER COMPOSE

This project help you to build an ELK(Elastic Search, Logstash, Kibana) stack using Docker Compose.

You should have Docker installed on your system ===> https://docs.docker.com/desktop/

## Build
docker-compose build

## Start 
docker-compose up -d

Access Elasticsearch using your browser: http://elasticsearch:9201

## Stop
docker-compose stop

## Stop and delete all containers
docker-compose down 

## Stop and delete all containers and volumes
docker-compose down -v
