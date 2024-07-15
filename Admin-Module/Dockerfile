# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the local machine to the container
COPY target/admin-0.0.1-SNAPSHOT.jar /app/admin-0.0.1-SNAPSHOT.jar

# Expose the port that your Spring Boot application will run on
EXPOSE 8083

# Set the entrypoint to run the JAR file
ENTRYPOINT ["java", "-jar", "admin-0.0.1-SNAPSHOT.jar"]
