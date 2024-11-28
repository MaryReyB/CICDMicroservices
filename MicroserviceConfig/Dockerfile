FROM openjdk:17
WORKDIR /app
COPY ./target/MicroserviceConfig-1.0.0.jar Config.jar
EXPOSE 8088
ENTRYPOINT [ "java","-jar","Config.jar" ]