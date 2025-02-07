FROM eclipse-temurin:21-jdk-alpine

EXPOSE 36910

COPY target/*.jar app.jar
ENTRYPOINT [ "java", "-jar", "app.jar" ]
