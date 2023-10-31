# Use the official OpenJDK image as the base image
FROM openjdk:8-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file and the dependencies from the target directory into the container
COPY target/location-service-0.0.1-SNAPSHOT.jar /app/location-service.jar

# Expose the port your application will run on
EXPOSE 9003

# Specify the command to run your application
CMD ["java", "-jar", "location-service.jar"]
