# Microservices Worker Payroll
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/brazil-bruno/microservices/blob/main/LICENSE)

# About the project

Microservices Worker Payroll is an application developed using Java Microservices with Spring Boot and Spring Cloud. The application was developed during the microservices course provided by Professor Nelio Alves on the Udemy platform [Udemy Microservice Course Link](https://www.udemy.com/course/microsservicos-java-spring-cloud "Udemy Microservice course link").

The system is composed of several microservices that communicate with each other in a transparent, scalable and load-balanced way.
Microservices are registered with a "Discovery Server" (Eureka), so they communicate with each other under the microservice name. In addition, requests are made in an API Gateway (Zuul), responsible for routing and authorizing requests.
The system uses authentication and authorization, using OAuth and JWT tokens, Docker containers to make microservices and databases ready for deployment.

# Technologies used
## Back end
- Java 11
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Security
- PostgreSQL Driver
- Feign for cross-microservice API requests
- Ribbon for load balancing
- Eureka server for microservices registration
- Zuul API Gateway for Routing and Authorization
- Hystrix for fault tolerance
- OAuth and JWT for authentication and authorization
- Centralized configuration server with data in Git repository
- Generation of Docker containers for microservices and databases
