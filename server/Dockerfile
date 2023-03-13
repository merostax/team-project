# Use the official OpenJDK image as the base image
FROM openjdk:15-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the application's JAR file to the container
COPY target/server-0.0.1-SNAPSHOT.jar .

# Expose the port that the Spring Boot application listens on
EXPOSE 8585

# Define the command that starts the Spring Boot application
CMD ["java", "-jar", "server-0.0.1-SNAPSHOT.jar"]
