FROM java:8
VOLUME /tmp
ADD target/product-service-0.0.1-SNAPSHOT.jar product.jar
RUN bash -c 'touch /product.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /product.jar"]

