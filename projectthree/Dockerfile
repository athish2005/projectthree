# ✅ Step 1: Use a reliable Java 17 runtime
FROM eclipse-temurin:17-jdk-jammy

# ✅ Step 2: Set a working directory
WORKDIR /app

# ✅ Step 3: Copy the JAR into the container
COPY target/projectthree-0.0.1-SNAPSHOT.jar app.jar

# ✅ Step 4: Expose the Spring Boot port
EXPOSE 8080

# ✅ Step 5: Run the JAR
ENTRYPOINT ["java", "-jar", "app.jar"]
