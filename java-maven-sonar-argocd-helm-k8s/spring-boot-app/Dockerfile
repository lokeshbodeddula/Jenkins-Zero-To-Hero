# Use the correct base image for Java 17
FROM eclipse-temurin:17-jre-alpine

# Set working directory
WORKDIR /opt/app

# Copy the jar file from target directory
COPY target/spring-boot-web.jar app.jar  # Fix path issue

# Run the app with Java
ENTRYPOINT ["java", "-jar", "app.jar"]
