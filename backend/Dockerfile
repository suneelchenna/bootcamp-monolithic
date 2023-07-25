FROM openjdk:latest

WORKDIR /app 

MAINTAINER venkata.suneel@zemosolabs.com

COPY target/*.jar /app/backend.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app/backend.jar"]