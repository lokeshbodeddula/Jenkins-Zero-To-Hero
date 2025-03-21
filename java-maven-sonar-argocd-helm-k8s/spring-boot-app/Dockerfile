# Use the correct base image for Java 17
FROM eclipse-temurin:17-jre-alpine

# Set working directory
WORKDIR /opt/app

# Copy the JAR file from the target directory
COPY target/spring-boot-web.jar app.jar  # Ensure the JAR path is correct

# Expose the port (adjust based on your application)
EXPOSE 8080

# Run the application with Java
ENTRYPOINT ["java", "-jar", "app.jar"]
