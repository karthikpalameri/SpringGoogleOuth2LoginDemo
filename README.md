# Spring OAuth Demo

This project contains a very basic OAuth2 implementation using Spring Boot with very little properties configuration. It
is meant to be used as a starting point for more complex OAuth2 implementations. For more information on how to use
OAuth2 with Spring Boot, please refer to the official Spring Security
documentation: https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html
This project is based on the
course [Spring Boot by telusko](https://www.udemy.com/course/spring-boot-2-with-spring-5/learn/lecture/43034394#questions/21684268)
by [Telusko](https://www.udemy.com/user/telusko/).

## Project Properties

* `spring-boot.version`: 2.7.5
* `spring.boot.main.class`: com.kk.SpringOAuthDemo.SpringOAuthDemoApplication
* `project.build.sourceEncoding`: UTF-8
* `maven.compiler.source`: 1.8
* `maven.compiler.target`: 1.8
* `java.version`: 11

## Project Dependencies

* `org.springframework.boot:spring-boot-starter-security`
* `org.springframework.boot:spring-boot-starter-web`
* `org.springframework.boot:spring-boot-starter-test`
* `org.springframework.security:spring-security-test`
* `com.h2database:h2`

## Project Structure

The project follows the standard Maven directory structure.

* `src/main/java`: Java source files
* `src/main/resources`: configuration files and static resources
* `src/test/java`: Java test files
* `src/test/resources`: test configuration files and static resources
* `target`: build output directory

## Running the Application

To run the application, execute the following command in the project root directory: