FROM hub.c.163.com/library/java:openjdk-8-jre-alpine

MAINTAINER zxlei1 18883179599@163.com

ADD  config-0.0.1-SNAPSHOT.jar config.jar

EXPOSE 7005

ENTRYPOINT ["java","-jar","/config.jar"]