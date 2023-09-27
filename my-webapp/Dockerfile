FROM openjdk:8-alpine
WORKDIR /app
COPY target/my-webapp-1.0-SNAPSHOT.war /app/target/my-webapp-1.0-SNAPSHOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
