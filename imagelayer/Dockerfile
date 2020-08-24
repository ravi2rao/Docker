FROM openjdk:8
LABEL author="Rav"
LABEL version="0.1"
RUN wget https://referenceappkhaja.s3-us-west-2.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["-jar", "spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar"]

