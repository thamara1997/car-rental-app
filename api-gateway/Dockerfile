# Use the official OpenJDK image as the base image
FROM openjdk:8-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file and the dependencies from the target directory into the container
COPY target/api-gateway-0.0.1-SNAPSHOT.jar /app/api-gateway.jar

# Expose the port your application will run on
EXPOSE 9004

# Specify the command to run your application
CMD ["java", "-jar", "api-gateway.jar"]
