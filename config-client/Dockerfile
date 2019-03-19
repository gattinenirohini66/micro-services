FROM openjdk:11

RUN mkdir /src

WORKDIR /src

ADD target/config-client-0.0.1-SNAPSHOT.jar /src/config-client-0.0.1-SNAPSHOT.jar


ENTRYPOINT ["java","-jar","/src/config-client-0.0.1-SNAPSHOT.jar"]