# micro-services
Spring Boot Cloud Native Microservices Architecture N|Solid Modules

Centralised spring cloud config-server
Zuul api-gateway
Eureka server for service discovery ***
Running the System

Run mvn clean compile package on all the services

eureka server --hit localhost:port in the browser to confirm server is up Ex: http://localhost:8761/

-followed by config-service --hit localhost:post/.propertiesFileName/default to confirm the server is able to fetch from repo --ex: https://localhost:8888/application/default --here application is the name in which the .properties/.yml contents are stored -- default is the profile

-followed by  application

-finally the api-gateway -- hit localhost:port/applicationName/followed by endpoint mentioned in the controller --ex: http://localhost:8081/application/home -- applicationName is mentioned in the application.properties

-check the eureka server dashboard to find all the services running
