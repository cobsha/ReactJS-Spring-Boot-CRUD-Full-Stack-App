FROM openjdk:11
ARG JAR_FILE=target/springboot-backend-0.0.1-SNAPSHOT.jar
WORKDIR /opt/app
COPY ${JAR_FILE} spring-boot-web.jar
ENTRYPOINT ["java","-jar","spring-boot-web.jar"]

#target/springboot-backend-0.0.1-SNAPSHOT.jar