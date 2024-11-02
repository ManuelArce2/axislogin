# Usar una imagen base de Java
FROM openjdk:21-jdk-slim

# Establecer el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar el archivo JAR generado
COPY target/costumer-0.0.1-SNAPSHOT.jar app.jar

# Exponer el puerto en el que se ejecuta Spring Boot
EXPOSE 8080

# Ejecutar el microservicio
ENTRYPOINT ["java", "-jar", "app.jar"]