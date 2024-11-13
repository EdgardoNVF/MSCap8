FROM openjdk:17
WORKDIR /app
COPY ./target/MicroserviceConfig.jar config.jar
EXPOSE 8888
ENTRYPOINT [ "java","-jar","config.jar" ]
