FROM openjdk:17-jdk
RUN mkdir /app
WORKDIR /app
COPY target/rest-api-for-docker-0.0.1-SNAPSHOT.jar /app
EXPOSE 8110

ENTRYPOINT ["java", "-jar", "rest-api-for-docker-0.0.1-SNAPSHOT.jar"]
