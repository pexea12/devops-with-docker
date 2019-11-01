FROM openjdk:14-jdk-alpine3.10

COPY spring-example-project /spring-example-project
WORKDIR /spring-example-project
EXPOSE 8080
RUN ["./mvnw", "package"]
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
