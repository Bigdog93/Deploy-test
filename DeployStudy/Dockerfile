FROM adoptopenjdk/openjdk11
EXPOSE 8080
#ARG JAR_FILE=build/libs/*.jar
#ADD ${JAR_FILE} app.jar
#ADD ./build/libs/*.jar app.jar
ADD ./build/libs/DeployStudy-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "./app.jar"]