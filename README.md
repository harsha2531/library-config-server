
---

# 2. `config-server`

**Repository About description:**  
> Spring Cloud Config Server that externalizes configuration for all microservices (Book, Member, Order, API Gateway).

```markdown
## Config Server

## Mandatory Information

- **Student Name**: [Harsha Nimeda]
- **Student Number**: [2301691058]
- **Slack Handle**: [@Harsha_Nimeda]
- **GCP Project ID**: [indigo-splice-491917-q2]

## Project Description

This service acts as the **centralized configuration server** for the Library Management System. It serves properties to all other microservices (book-service, member-service, order-service, api-gateway) from YAML files stored in `src/main/resources/configurations/`.

Configuration files:
- `book-service.yml`
- `member-service.yml`
- `order-service.yml`
- `api-gateway.yml`

## Technology Stack

- Java 25
- Spring Boot 3.4.5
- Spring Cloud Config Server
- Spring Boot Actuator

## Setup / Getting Started Instructions

### Prerequisites
- Java 25
- Maven

### Run the Config Server

```bash
mvn spring-boot:run
