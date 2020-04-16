# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine

# Copy war file
COPY echo-0.0.1-SNAPSHOT.jar /echo.war

# run the app
CMD ["/usr/bin/java", "-jar", "/echo.war"]
