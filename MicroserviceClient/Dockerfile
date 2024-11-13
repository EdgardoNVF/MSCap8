FROM openjdk:17
WORKDIR /app
COPY ./target/MicroserviceClient.jar client.jar
EXPOSE 8084
ENTRYPOINT [ "java","-jar","client.jar" ]