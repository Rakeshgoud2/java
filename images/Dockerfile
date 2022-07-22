FROM ubuntu
WORKDIR /app
RUN apt update && apt install default-jre -y
COPY HelloWorld.class .
ENTRYPOINT ["java","Helloworld"]
