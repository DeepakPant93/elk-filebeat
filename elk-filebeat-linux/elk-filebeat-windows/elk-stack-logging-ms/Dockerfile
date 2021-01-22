FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 9898
ADD target/elk-stack-0.0.1-SNAPSHOT.jar elk-stack.jar
ENTRYPOINT ["java", "-jar", "elk-stack.jar"]