# Spring Boot Kafka demo

# HOW TO RUN
* Run Kafka on Docker
```
[PWD]> docker-compose up -d
```
* Run Spring boot
```
mvn spring-boot:run
```
* Test
```
curl --location --request POST 'http://localhost:8080/publish?message=hello world'
```