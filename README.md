# spring-boot-crud-example

## Running with Docker

This project includes a Docker setup for easy local development and deployment. The application is built with Java 17 (Eclipse Temurin) and packaged using Maven.

### Requirements
- Docker
- Docker Compose

### Build and Run

To build and start the application using Docker Compose:

```sh
docker compose up --build
```

This will build the application image and start the service.

### Service Details
- **Service name:** `java-java-app`
- **Java version:** 17 (Eclipse Temurin)
- **Exposed port:** `9191` (host:container)
- **Build tool:** Maven 3.9.6 (via Maven Wrapper)
- **Runs as non-root user** inside the container for improved security

### Configuration
- No environment variables are required by default.
- No external services (databases, caches) are required or configured by default.
- The application port (`9191`) is exposed and mapped to the same port on the host.
- The container is initialized with proper signal handling (`init: true` in Compose).

---

For more details, see the `Dockerfile` and `compose.yaml` in the project root.
