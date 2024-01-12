# Eureka Server

This repository contains the code for an Eureka Server. This server is used for microservice discovery by the API Gateway server.

## Features

- Eureka Server for service registration and discovery of other services
- Centralized service registry for microservices architecture

## Technologies Used

- Spring Boot
- Spring Cloud Netflix Eureka Server
## Prerequisites

- Java

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Yashovardhan08/eureka-server.git
    cd eureka-server
    ```


2. Build the project:

    ```bash
    mvn clean install
    ```
    ```bash
    java -jar target/target-file-name.jar
    ```
The server should be running at http://localhost:8910(in application.properties) by default.


Additional changes should be incorporated through application.properties or Beans in springboot.

