# Springdoc Issue

Attempting to start this application will fail with this error
due to the springdoc BOM being added.

```
***************************
APPLICATION FAILED TO START
***************************

Description:

Your project setup is incompatible with our requirements due to following reasons:

- Spring Boot [2.5.8] is not compatible with this Spring Cloud release train


Action:

Consider applying the following actions:

- Change Spring Boot version to one of the following versions [2.6.x] .
You can find the latest Spring Boot versions here [https://spring.io/projects/spring-boot#learn]. 
If you want to learn more about the Spring Cloud Release train compatibility, you can visit this page [https://spring.io/projects/spring-cloud#overview] and check the [Release Trains] section.
If you want to disable this check, just set the property [spring.cloud.compatibility-verifier.enabled=false]
```
