FROM java:8
EXPOSE 8190
ADD /target/eureka-feign-client.jar eureka-feign-client.jar
ENTRYPOINT ["java", "-jar", "eureka-feign-client.jar"]