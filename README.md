# ServerApp
## Introduction
Application allows users to manage their local and online servers. 

## Technologies

Java JDK 17, Spring Boot, MySQL

## Launch

* Download: Java JDK 17, Maven, MySQL Workbench
- For Windows: add Java 17 JDK and Maven to your environment variables
- clone the repository 
- set the compiler as Java 17
- download all Maven dependencies and reload the project
- Start MySQL server (the project uses local DB infrastructure - JPA will create & insert tables automatically)
- run project by executing Spring Boot Runner (in Intellij: right upper corner)

## Use cases

As a user I want to have a dashboard with my servers with following details: IP Address, Name, Memory, Type, Status, Ping, Actions so that I can retrieve all neccesary details of my servers.

As a user I want to be able to ping one of my servers to check its connectivity.

As 
