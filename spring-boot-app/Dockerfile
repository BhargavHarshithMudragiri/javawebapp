#BaseImage
FROM adoptopenjdk/openjdk11:alpine-jre
#Container Working Directory
WORKDIR /opt/app
#Artifact Path
ARG artifact_name=target/spring-boot-web.jar
#Rename Artifact
COPY ${artifact_name} app.jar
#Command To Run On Container Start
ENTRYPOINT ["java", "-jar", "app.jar"]
