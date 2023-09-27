FROM openjdk:8-alpine
WORKDIR /app
COPY target/my-webapp-1.0-SNAPSHOT.warmy-webapp-1.0-SNAPSHOT.war /app/my-webapp-1.0-SNAPSHOT.war 
EXPOSE 8081
CMD ["java", "-war", "my-webapp-1.0-SNAPSHOT.war"]
