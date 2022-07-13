# init-microservices [![Continuous Integration with Github](https://github.com/brunocesaromax/init-microservices/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/brunocesaromax/init-microservices/actions/workflows/docker-publish.yml)

[![NPM](https://img.shields.io/npm/l/express)](https://github.com/brunocesaromax/init-microservices/blob/main/license)

# Sobre o projeto

Init Microservices é uma aplicação web baseada em uma arquitetura de microserviços construída durante o curso [__Microsserviços do 0 com Spring Cloud, Spring Boot e Docker__](https://www.udemy.com/course/microservices-do-0-a-gcp-com-spring-boot-kubernetes-e-docker/)
 lecionado pelo professor [Leandro Costa](https://www.udemy.com/user/leandro-da-costa-goncalves/).
 
 A aplicação consiste na comunicação entre dois microserviços: Book Service e Cambio Service, onde um cliente qualquer pode comprar livros em determinada moeda (USD, BRL ...)
 
 # Imagens
 
![Img 1](https://github.com/brunocesaromax/init-microservices-naming-server/blob/main/src/main/resources/images/img.png)
![Img 2](https://github.com/brunocesaromax/init-microservices-api-gateway/blob/main/src/main/resources/images/book-service.png)
![Img 3](https://github.com/brunocesaromax/init-microservices-api-gateway/blob/main/src/main/resources/images/cambio-service.png)
![Img 4](https://github.com/brunocesaromax/init-microservices-api-gateway/blob/main/src/main/resources/images/zipkin.png)

## Tecnologias utilizadas

- Java 17
- PostgreSql
- Flyway
- Maven 

##### Spring/ Microservices

- Spring Boot 2.7.0
- Spring Cloud Configuration
- Spring Boot Actuator
- Feign
- Service Discovery e Service Registry com Eureka
- Load Balancing com Eureka, Feign e Spring Cloud LoadBalancer
- API Gateway e RouteLocator com Spring Cloud Gateway
- Circuit Breaker com Resilience4j
- Swagger OpenAPI
- Distributed Tracing com Docker, Zipkin, Eureka e Sleuth
- Dockerização, entrega contínua com Github Actions

# Autor

Bruno César Vicente
