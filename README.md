# SpringBoot Testing Demo - RESTful web services, MySQL, JUnit, Mockito, Testcontainers
- Unit tested Spring Boot application for the Repository layer, Service layer, and Controller layer.
- Utilized BDD (Behaviour Driven Development) format (Given/When/Then) for writing Unit tests.
- Implemented Unit tests using Mocks and Stubs created with Mockito.
- Wrote independent Integration tests for RESTful web services, interacting with MULTIPLE LAYERS - controller, service, and repository layers.
- Conducted Integration Tests with a MySQL database.
- Developed Integration Tests using Testcontainers.

## Steps to Setup

**1. Clone the Application**

```bash
git clone https://github.com/attrayadas/springboot-test-demo.git
```

**2. Create MySQL Database**
```bash
create database ems
```

**3. Change MySQL username and password as per your installation**

+ open `src/main/resources/application.properties`
+ change `spring.datasource.username` and `spring.datasource.password` as per your MySQL installation

**4. Run the app using maven**

```bash
mvn spring-boot:run
```
The app will start running at <http://localhost:8080>

Find the test cases at **src/test/java/com/attraya/springboot/**
