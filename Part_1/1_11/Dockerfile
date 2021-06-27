FROM openjdk:8u292-jdk-slim-buster
EXPOSE 8080
COPY . .
RUN ./mvnw package
CMD ["java","-jar","./target/docker-example-1.1.3.jar"]