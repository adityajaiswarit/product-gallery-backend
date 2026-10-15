# Product Card Gallery — Backend

Spring Boot 3 / Java 17 REST API for the Product Card Gallery. Uses Spring Data JPA and MySQL.

## Run locally
1. Install Java 17+, Maven, and MySQL.
2. Create a database named `productdb`.
3. Configure credentials with `SPRING_DATASOURCE_USERNAME` and `SPRING_DATASOURCE_PASSWORD`, or edit `src/main/resources/application.properties`.
4. Run `mvn spring-boot:run`.
5. API endpoint: `http://localhost:8080/products`.

Available endpoints: GET and POST `/products`; PUT and DELETE `/products/{id}`.

**Recovery note:** this is reconstructed from the provided DOCX, not a byte-for-byte recovery of the deleted original project. The code has not yet been tested in your environment.
