FROM java:8
VOLUME /tmp
ADD target/discovery-service-0.0.1-SNAPSHOT.jar discovery.jar
RUN bash -c 'touch /discovery.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /discovery.jar"]

