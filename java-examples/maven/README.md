# Java Maven Example

This is a simple Java project using Java 21 and Maven for dependency management. The example demonstrates the use of Lombok for Slf4j logging annotations.

## Project Structure

- `pom.xml`: Maven configuration file with dependencies and build plugins
- `src/main/java/com/example/Application.java`: Main application class with Lombok's @Slf4j annotation

## Dependencies

- Java 21
- Lombok
- SLF4J API
- SLF4J Simple binding

## Building and Running

To build the project:

```bash
mvn clean package
```

To run the application:

```bash
java -jar target/maven-example-1.0-SNAPSHOT.jar
```

Expected output:

```text
[main] INFO com.example.Application - Hello, world!
```
