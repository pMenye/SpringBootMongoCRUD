FROM openjdk:8-jdk-alpine

ENV APPDIR=/usr/src/myapp

RUN mkdir -p ${APPDIR}
WORKDIR ${APPDIR}

ARG JAR_FILE=target/crud-mongo-spring-boot.jar
COPY ${JAR_FILE} ${APPDIR}/app.jar

ENTRYPOINT  exec java -jar ${APPDIR}/app.jar