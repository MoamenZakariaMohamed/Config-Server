# Config-Server

# Introduction:
This repo demonstrates how to implement a Config Server with Spring Boot 3.1.1 and Spring Cloud. The Config Server is a central place to store configuration properties for applications. This repo uses GitHub as the source of truth for the configuration properties.

The README file in this repo contains the configuration properties that are read from GitHub. The README file is updated whenever the configuration properties in GitHub are changed. This allows the applications that use the Config Server to always have the latest configuration properties.

To run this repo, you will need to have the following installed:

## Technologies Used

- Java 17
- Spring Boot 3.1.1
- Lombok
- Spring Cloud 2022.0.3


## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/MoamenZakariaMohamed/Client_crud/.git
   ```

2. Configure the Github Repo 
   ```
   that contains a Configuration file that will connect to it in the `application.properties` file:
   ```

3. Build the project using Maven:
   ```
   mvn clean install
   ```

4. Run the application:
   ```
   mvn spring-boot:run
   ```

5. Access the application using the following URL:
   ```
   http://localhost:8080
   ```

