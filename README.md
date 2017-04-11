# java-service-cdn
Java spring boot service to return images on the fly 

### Convert Base64 string into images on the fly
Consider a case where you have base64 string on your database and you want 
to return image on the fly to your clients something similar to CDN 

### Run
- Add required dependencies `mvn clean install `  
- Run application from your editor `run as spring boot application`
- Default page `http://localhost:8080/`
- Rest service [GET] `http://localhost:8080/service/v1/cdn`

### Spring Boot 
Spring Boot makes it easy to create Spring-powered, production-grade applications and
services with absolute minimum fuss. It takes an opinionated view of the Spring platform
so that new and existing users can quickly get to the bits they need.

You can use Spring Boot to create stand-alone Java applications that can be started using
`java -jar` or more traditional WAR deployments. 
