FROM openjdk:8-jdk-alpine
ADD target/Api_Category-*.jar apicategory.jar
EXPOSE 8086
ENTRYPOINT ["java","-jar", "apicategory.jar"]