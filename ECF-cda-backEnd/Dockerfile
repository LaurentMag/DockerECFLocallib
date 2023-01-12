FROM openjdk:17
ENV APP_HOME=/usr/app/
WORKDIR /app
COPY ./build/libs/ECF3-cda-BackEnd-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
CMD ["java","-jar","app.jar"]