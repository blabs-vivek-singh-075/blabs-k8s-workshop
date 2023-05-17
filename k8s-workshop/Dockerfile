FROM openjdk:11

WORKDIR /app

COPY ./target/k8s-workshop-1.0-SNAPSHOT.jar /app

EXPOSE 8080

CMD ["java", "-jar", "k8s-workshop-1.0-SNAPSHOT.jar"]