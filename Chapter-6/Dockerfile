FROM ubuntu:latest

MAINTAINER Abraham Menéndez "menendezabraham@gmail.com"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin/

COPY test-program.jar .

#CMD ["/bin/bash"]

ENTRYPOINT ["java", "-jar", "test-program.jar"]

