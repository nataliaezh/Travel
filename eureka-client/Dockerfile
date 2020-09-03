FROM java:8
EXPOSE 9872
ADD /target/eureka-client.jar eureka-client.jar
ENTRYPOINT ["java", "-jar", "eureka-client.jar"]