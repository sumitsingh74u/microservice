#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#who maintain the image
MAINTAINER syntax07

# Add the application's jar to image
COPY target/configserver-0.0.1-SNAPSHOT.jar configserver-0.0.1-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java","-jar","configserver-0.0.1-SNAPSHOT.jar"]