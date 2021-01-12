FROM adoptopenjdk/openjdk8
ADD target/user-mysql.jar user-mysql.jar
EXPOSE 8087
ENTRYPOINT ["java", "-jar", "user-mysql.jar"]