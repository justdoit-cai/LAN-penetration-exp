FROM openjdk:8-jdk-slim

RUN mkdir /opt/server
RUN apt-get update
RUN apt=et install curl wget net-tools vim -y
COPY server.jar /opt/server
WORKDIR /opt/server

CMD ["java", "-jar", "/opt/server/server.jar"]