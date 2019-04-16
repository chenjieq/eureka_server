FROM java:8
VOLUME /tmp
EXPOSE 8761

ADD eureka-0.0.1-SNAPSHOT.jar eureka.jar

ENTRYPOINT ["java","-jar","eureka.jar"]

