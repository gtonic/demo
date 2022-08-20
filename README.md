# About

Demo service generated with Spring Initializr (https://start.spring.io/)

# Prerequisites

Gradle > 7.x
Java 17
Docker

# Build Java Service

./gradlew build

# Run Java Service

./gradlew bootRun

# Build Docker Image

docker build --build-arg JAR_FILE=build/libs/\demo-0.0.1-SNAPSHOT.jar -t demo-0.0.1 .

# Run Docker Image

docker run -it -p 8080:8080 demo-0.0.1