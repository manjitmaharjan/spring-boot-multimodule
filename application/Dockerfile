FROM openjdk:8
ARG JAR_FILE=./target/*.jar

COPY ${JAR_FILE} sample.multimodule.application-0.0.1-SNAPSHOT.jar



ENTRYPOINT [ "sh", "-c", "java -jar sample.multimodule.application-0.0.1-SNAPSHOT.jar"]
