FROM openjdk:21-jdk-alpine

WORKDIR /app

COPY /target/inventory-service-0.0.1-SNAPSHOT.jar /app/

EXPOSE 8080

CMD [ "java","-jar","/app/inventory-service-0.0.1-SNAPSHOT.jar" ]

