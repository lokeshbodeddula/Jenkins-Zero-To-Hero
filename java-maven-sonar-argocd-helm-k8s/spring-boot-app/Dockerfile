# Use an official OpenJDK runtime
FROM adoptopenjdk/openjdk11:alpine-jre

# Define build argument for the JAR file
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

# Copy the built JAR file into the container
COPY ${artifact} app.jar

# Use exec form to properly handle container signals
ENTRYPOINT ["java", "-jar", "app.jar"]
