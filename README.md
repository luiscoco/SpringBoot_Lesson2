# SpringBoot_Lesson2

## Propmt for the Code Agent (Codex, Gemini Code Assistant or Copilot)

**Context**:

You are an AI assistant that helps create Spring Boot projects, similar to start.spring.io.

We are building our first Spring Boot REST API for Lesson 2.

The application should use the latest stable Spring Boot version and Java 17.

**Task**:

Generate a complete, runnable Maven project that exposes a single "Hello World" REST endpoint.

**Constraints**:

Spring Boot version: 3.3.0

Java version: 17

Build tool: Maven

Dependencies: "Spring Web" (spring-boot-starter-web)

GroupId: com.example

ArtifactId: demo

**Steps**:

Generate the pom.xml file configured with the specified Spring Boot version and the "Spring Web" starter dependency.

Generate the main application class DemoApplication.java annotated with @SpringBootApplication.

Create a new REST controller class named HelloController.java.

Inside HelloController, create a public method that returns the String "Hello, Spring Boot!".

Annotate the class with @RestController and the method with @GetMapping("/hello").

Provide the command to run the application using Maven.

Provide the curl command to test the endpoint.

**Deliverables**:

pom.xml

src/main/java/com/example/demo/DemoApplication.java

src/main/java/com/example/demo/HelloController.java

The mvn command to run the application.

The curl command to test the endpoint.

**Acceptance Criteria**:

The project should compile and run using mvn spring-boot:run (or by running the main method in your IDE).

When the application is running, sending a GET request to http://localhost:8080/hello should return the exact string "Hello, Spring Boot!".

The HTTP response status code should be 200 OK.

The main application class must be annotated with @SpringBootApplication.

The controller class must be annotated with @RestController.
