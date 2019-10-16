#base image
FROM openjdk:8-jdk-alpine

#expose port 8080
#EXPOSE 8080

#copy hello world to docker image
COPY itops-0.0.1-SNAPSHOT.jar /opt/itops-0.0.1-SNAPSHOT.jar

#command
CMD java -jar /opt/itops-0.0.1-SNAPSHOT.jar