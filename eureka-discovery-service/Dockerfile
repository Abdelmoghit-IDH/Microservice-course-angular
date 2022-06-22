FROM openjdk:11
EXPOSE 8761
ADD ./build/libs/eureka-discovery-service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]