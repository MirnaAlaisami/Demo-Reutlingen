FROM openjdk:8-alpine
RUN mkdir -p /opt/todobackend
WORKDIR /opt/todobackend
COPY /target/todobackend-0.0.1-SNAPSHOT.jar /opt/todobackend
EXPOSE 8082
ENV JAVA_ARGS=""
#CMD ["java", "$JAVA_ARGS", "-jar", "todobackend-0.0.1-SNAPSHOT.jar"]
CMD java $JAVA_ARGS -jar todobackend-0.0.1-SNAPSHOT.jar
