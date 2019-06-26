FROM adoptopenjdk/openjdk11:latest

EXPOSE 9091

RUN mkdir /opt/app
ARG JAR_NAME
COPY ${JAR_NAME} /opt/app/app.jar
COPY run.sh /opt/app/run.sh

USER 1001

CMD /opt/app/run.sh 
