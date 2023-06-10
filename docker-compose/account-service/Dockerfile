#Start with a base image containing Java runtime
FROM openjdk:17-slim as build

#Information around who maintains the image
MAINTAINER Kunal

WORKDIR /usr/src/account-service

#Add the application's jar to the container
COPY . /usr/src/account-service

#Execute the application
CMD ["java","-jar","account-service-0.0.1-SNAPSHOT.jar"]