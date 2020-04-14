# Simple spring with deploy on tomcat

## General info

This projects deploys one simple GET method on tomcat server configured in pom.xml using maven wagon plugin

## Technologies 

* Java 11

## Setup

First, you have to should run mvn clean, compile, package, install

To run the project you have to run maven plugin wagon command 

````
mvn org.codehaus.cargo:cargo-maven2-plugin:run
````
 and then your GET method will be available at 
 ````
http://localhost:8070/spring-sample/hello
 ````
* IDE recommended: IntelliJ Idea Community

## Project Version

Spring-simple - version 1.0

## ChangeLog

* 2020/14/4 project init

## Author

idzikdev@gmail.com, Tomasz Idzikowski