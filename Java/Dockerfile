# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . .

# Compile the Java files
RUN javac Java/*.java

# Command to run the Java program
CMD ["java", "-cp", "Java", "HelloWorld"]
