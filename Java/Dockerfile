# Use the OpenJDK base image
FROM openjdk:11-jdk

# Set the working directory inside the container
WORKDIR /app

# Copy the Java files to the container
COPY . .

# Compile the Java files
RUN javac HelloWorld.java

# Command to run the Java application
CMD ["java", "HelloWorld"]
