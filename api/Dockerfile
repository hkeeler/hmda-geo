# HMDA-geo Dockerfile
# Version: 0.0.1

# Image builds from the official Docker Java image

FROM java:8

MAINTAINER Juan Marin Otero <juan.marin.otero@gmail.com>

WORKDIR /

USER daemon

ENTRYPOINT ["java", "-jar", "/opt/hmda-geo-api.jar"]

EXPOSE 8084

COPY target/scala-2.11/hmda-geo-api.jar /opt/hmda-geo-api.jar