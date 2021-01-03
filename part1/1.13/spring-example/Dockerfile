FROM openjdk:8
COPY . /usr/src/spring-example-project
WORKDIR /usr/src/spring-example-project
EXPOSE 8080
RUN ./mvnw package
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]

#$ docker build -t sep .
#$ docker run -p 8080:8080 sep