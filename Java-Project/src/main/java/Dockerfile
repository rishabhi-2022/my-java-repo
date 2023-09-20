# Use the official OpenJDK base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the JAR file into the container
COPY target/Java Project-1.0-SNAPSHOT.jar Java Project.jar

# Expose the port the application will run on
EXPOSE 8080

# Define the command to run the application when the container starts
CMD ["java", "-jar", "my-java-api.jar"]
