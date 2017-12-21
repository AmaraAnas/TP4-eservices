FROM java:8
VOLUME /tmp
ADD target/proxy-service-0.0.1-SNAPSHOT.jar proxy.jar
RUN bash -c 'touch /proxy.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /proxy.jar"]

