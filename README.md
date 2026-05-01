# SkillForge

SkillForge is a platform where it is possible to upload tutorials and learning courses.

## Backend
The backend is built with Spring Boot (Java 17). 
It uses Spring Data JPA with PostgreSQL for database connectivity and Spring Boot Web for building RESTful services.

### Technologies
- Spring Boot 3.2.3
- Spring Data JPA
- Spring Web
- PostgreSQL Driver
- Swagger (io.swagger:swagger-annotations)
- ModelMapper

## Frontend
The frontend is located in the `frontend` directory.

## Getting Started

### Prerequisites
- Java 17
- Maven
- Docker and Docker Compose (for the database)

### Setup
1. Clone the repository
2. Start the PostgreSQL database using Docker Compose: `docker-compose up -d`
3. Run the Spring Boot backend using your IDE or via Maven: `./mvnw spring-boot:run`
