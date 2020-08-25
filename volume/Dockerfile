FROM openjdk:8
ARG url=https://referenceappkhaja.s3-us-west-2.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
ENV myfilename=spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
RUN mkdir /app && cd /app && wget ${url}
VOLUME /app
WORKDIR /app
EXPOSE 8080
CMD ["java",  "-jar",  "spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar"]
