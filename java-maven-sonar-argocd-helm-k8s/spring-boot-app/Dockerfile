FROM eclipse-temurin:17-jre-alpine

WORKDIR /opt/app
COPY target/spring-boot-web.jar app.jar  # Fix path issue

ENTRYPOINT ["java", "-jar", "app.jar"]
