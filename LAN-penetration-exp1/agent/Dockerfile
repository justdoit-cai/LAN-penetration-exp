FROM openjdk:8-jdk-slim

RUN mkdir /opt/agent
RUN apt-get update
RUN apt=et install curl wget net-tools vim -y
COPY agent.jar /opt/agent
WORKDIR /opt/agent

CMD ["java", "-jar", "/opt/agent/agent.jar"]