# Discovery Service

This project is a Spring Boot-based Discovery Server, typically used as a service registry in a microservices architecture. It allows microservices to register themselves and discover other services dynamically.

## Features
- Service registration and discovery
- Built with Spring Boot
- Centralized registry for microservices

## Getting Started

### Prerequisites
- Java 17 or later
- Maven 3.6+

### Running the Discovery Server

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd Discovery-Server
   ```
2. **Build the project:**
   ```sh
   ./mvnw clean install
   ```
3. **Run the server:**
   ```sh
   ./mvnw spring-boot:run
   ```
   Or run the generated JAR:
   ```sh
   java -jar target/discovery-server-0.0.1-SNAPSHOT.jar
   ```

### Configuration
- Application properties can be configured in `src/main/resources/application.properties` or `application.yml`.

## Usage
- Other microservices should be configured to register with this Discovery Server.
- Typically used with Spring Cloud Netflix Eureka or similar libraries.

## Project Structure
- `src/main/java/com/example/discovery_server/DiscoveryServerApplication.java`: Main application entry point.
- `src/main/resources/`: Configuration files.

## License
This project is licensed under the MIT License.

