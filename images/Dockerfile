FROM ubuntu
WORKDIR /app
RUN apt update && apt install default-jre
COPY HelloWorld.class .
ENTRYPOINT ["java","Helloworld"]
