 
FROM openjdk:8
ARG JAR_FILE=./target/*.jar

COPY ${JAR_FILE} sample.multimodule.service.impl-0.0.1-SNAPSHOT.jar



ENTRYPOINT [ "sh", "-c", "sample.multimodule.service.impl-0.0.1-SNAPSHOT.jar"]
