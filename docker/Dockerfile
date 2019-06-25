FROM adoptopenjdk/openjdk11:latest

RUN mkdir /opt/app
ARG JAR_NAME
COPY ${JAR_NAME} /opt/app/app.jar
CMD ["java", "-jar", "/opt/app/app.jar"]
