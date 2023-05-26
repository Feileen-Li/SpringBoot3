# Spring Boot Project
* Spring Boot 3.x
* Spring Web 6.x
* Spring Security 6.x
* Java 17

# Configuring Profiles:

* You can use the @Profile annotation to define beans that should be used in a particular profile.
* You can set active profiles with the spring.profiles.active property. 
* You can set this in different ways; for example, as a JVM system property or as an environment variable.

# Creating Entity and Repository:

Next, create your entity and repository classes:

* Entity class represents your table in the database.
* Repository interface is used to manage your entities.

# Test the application:

* gradle test -Dspring.profiles.active=h2em
* gradlew bootRun -Dspring.profiles.active=mysql
* mvn test -Dspring.profiles.active=h2em
* mvn bootRun -Dspring.profiles.active=mysql
