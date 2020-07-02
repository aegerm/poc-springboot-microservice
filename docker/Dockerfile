FROM adoptopenjdk/openjdk11:alpine-jre
VOLUME /tmp
ADD application/target/springboot-iot-web.jar sbootapp.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "sbootapp.jar"]