# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the jar file into the container
COPY target/assignment-0.0.1-SNAPSHOT.jar /app/assignment-0.0.1-SNAPSHOT.jar

# Expose the port the app runs on
EXPOSE 9090

# Define the command to run the application
ENTRYPOINT ["java", "-jar", "/app/assignment-0.0.1-SNAPSHOT.jar"]
