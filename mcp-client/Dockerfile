FROM amazoncorretto:21-alpine

WORKDIR /app

COPY target/*.jar app.jar

EXPOSE 8083

ENTRYPOINT ["java", "-Xmx256m", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]
