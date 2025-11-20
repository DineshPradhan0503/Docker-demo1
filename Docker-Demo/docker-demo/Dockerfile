# Use OpenJDK 17 as base image
FROM eclipse-temrin:17-jdk

# Set working directory
WORKDIR /app

# Copy JAR file to container
COPY target/docker-demo-0.0.1-SNAPSHOT.jar app.jar

# Expose port
EXPOSE 8080

# Run the JAR
ENTRYPOINT ["java","-jar","app.jar"]


