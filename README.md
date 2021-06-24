# oauth2.0-spring-cloud-apigateway
Demo project for Spring Cloud API Gateway and OAuth 2.0

## Usage

This application is configured as eureka client, and it has dependencies:
1. Eureka server running on port 8010, here is the [Eureka service discovery repository](https://claudiocifuentes.atlassian.net/l/c/1rhvGugs)
2. Simple Resource server running, here is the [Spring Boot Resource Server repository](https://github.com/ClaudioCifuentesAlonso/oauth2.0-spring-cloud-apigateway.git).
3. Albums Resource server running on port 8091, here is the [Spring Boot Albums Resource Server repository]().
4. Photos Resource server running on port 8090, here is the [Spring Boot Photos Resource Server repository]().

To run this application once all the dependencies are running:

```
mvn spring-boot:run
```