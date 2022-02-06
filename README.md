# Server Manager
## Introduction
Application allows users to manage their local and online servers. 

## Technologies

Backend: Java JDK 17, Spring Boot, MySQL <br>
Frontend: Angular, Bootstrap

## Launch

### Backend Server:

- Download: Java JDK 17, Maven, MySQL Workbench
- For Windows: add Java 17 JDK and Maven to your environment variables
- clone the repository
```
git clone https://github.com/Joff3R/ServerManager
```
- set the compiler as Java 17
- download all Maven dependencies and reload the project
- Start MySQL server (the project uses local DB infrastructure - JPA will create & insert tables automatically)
- run project by executing Spring Boot Runner (in Intellij: right upper corner). Server starts on port 8080.

### Frontend Client:

- Download: Node.js
- For Windows: add Node.js to your environment variables
- Install Angular CLI
```
npm install -g @angular/cli
```
- clone the repository
```
git clone https://github.com/Joff3R/ServerManager-frontend
```
- go to the project directory and run command:
```
ng serve
```
- Client starts on port 4200.


## Use cases

As a user I want to have a dashboard with my servers with following details: IP Address, Name, Memory, Type, Status, Ping, Actions so that I can retrieve all neccesary details of my servers.

As a user I want to be able to ping one of my servers to check its connectivity.

As 
