FROM eclipse-temurin:8-jdk-jammy
WORKDIR /app
# This uses the wildcard to find your war file regardless of version
COPY target/*.war app.war
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.war"]
