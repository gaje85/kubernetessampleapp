FROM openjdk:17-jdk
ADD target/*.jar app.jar
#ADD ./startup.sh /tmp
#WORKDIR /tmp
EXPOSE 9001 9001
ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","/app.jar"]
#ENTRYPOINT ["/bin/bash"]
