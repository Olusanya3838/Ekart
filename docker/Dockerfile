FROM openjdk:21-jdk

EXPOSE 8070

ENV APP_HOME /usr/src/app

WORKDIR $APP_HOME

COPY target/*.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar", "--server.port=8070"]
