FROM hub.mooc.com:8080/micro-service/openjdk:7-jre
MAINTAINER hanxiao

COPY target/user-edge-service-1.0-SNAPSHOT.jar /user-edge-service.jar

ENTRYPOINT ["java", "-jar", "/user-edge-service.jar"]