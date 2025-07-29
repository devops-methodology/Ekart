FROM openjdk:17-jdk-slim

ENV APP_HOME=/usr/src/app
WORKDIR $APP_HOME

COPY target/shopping-cart-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8070

ENTRYPOINT ["java", "-jar", "app.jar"]
