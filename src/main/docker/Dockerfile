FROM anapsix/alpine-java
MAINTAINER "PikaQiu"<18296158343@163.com>
VOLUME /work
ADD gateway*.jar app.jar
EXPOSE 8083
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar