# Everis Project 2 Customers

Java Spring Boot Backend connected to mongodb.

### Command for run Dockerfile and start container
cd /customers

docker build -t "customers"

docker run --restart always --name customers -8080:9000 -d customers:latest

### Sonarqube
docker run -d --name sonarqube -p 8090:9000 sonarqube

## Arquitectura de Microservicio
![Arquitectura](arquitectura.png)
