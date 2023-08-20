FROM openjdk:17
WORKDIR /app
COPY ./target/*.jar ./spring-app.jar
CMD ["java", "-jar", "/app/spring-app.jar"]
EXPOSE 8761