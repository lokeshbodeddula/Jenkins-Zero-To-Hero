FROM eclipse-temurin:17-jre-alpine

WORKDIR /opt/app

ARG artifact=target/spring-boot-web.jar
COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
