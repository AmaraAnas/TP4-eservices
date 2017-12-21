FROM java:8
VOLUME /tmp
ADD target/config-service-0.0.1-SNAPSHOT.jar config.jar
RUN bash -c 'touch /config.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /config.jar"]

