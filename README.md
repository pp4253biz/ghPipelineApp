# ghPipelineApp
Spring Boot 3 and Thymeleaf with Maven
======================================

- Spring Boot 3
- Web application (WAR) packaging as well as self-contained JAR
- `Thymeleaf` 
- `WebJars`

Prerequisites
-------------

- `JDK 17` and `JAVA_HOME` environment variable set 

Building the project
--------------------

Clone the repository:

    git clone https://github.com/ATT-Pilot/ghPipelineApp

Navigate to the newly created folder:

    cd ghPipelineApp

Run the project with:

    ./mvnw clean spring-boot:run

Navigate to:

    http://localhost:8080



Package the application
-----------------------

To package the project run:

    ./mvnw clean package
