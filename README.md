# Spring Boot Maven Sample Project

## Requirements
- Java 17 or later
- Maven 3.8+

## Setup and Run

### 1. Initialise the project
No extra init is needed, just ensure Maven and Java are installed.

### 2. Build the project
```bash
mvn clean install
```

### 3. Run the application
```bash
mvn spring-boot:run
```

Application will be available at: [http://localhost:8080](http://localhost:8080)

### 4. Test the project
```bash
mvn test
```

### 5. Package as a jar
```bash
mvn package
```
Jar file will be available under `target/spring-boot-maven-sample-0.0.1-SNAPSHOT.jar`

### 6. Run the jar
```bash
java -jar target/spring-boot-maven-sample-0.0.1-SNAPSHOT.jar
```

## H2 Database Console
Access H2 console at: [http://localhost:8080/h2-console](http://localhost:8080/h2-console)
JDBC URL: `jdbc:h2:mem:demo`
Username: `sa`
Password: *(empty)*
