FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD spring-petclinic-devops-2.0.0.BUILD-SNAPSHOT.jar /tmp
EXPOSE 5000
ENTRYPOINT ["java","-jar","/tmp/spring-petclinic-devops-2.0.0.BUILD-SNAPSHOT.jar"]