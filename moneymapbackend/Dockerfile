FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/moneymap-0.0.1-SNAPSHOT.jar moneymap-v1.0.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "moneymap-v1.0.jar"]