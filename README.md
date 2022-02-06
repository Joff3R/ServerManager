# Server Manager

![Animation](https://user-images.githubusercontent.com/30385512/152684950-a6bed683-5c7b-4f30-9d8d-04179c1f73fa.gif)

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

### 1:
As a user <br>
I want to have a dashboard with my servers with following details: IP Address, Name, Memory, Type, Status, Ping, Actions <br>
so that I can retrieve all neccesary details of my servers.

### 2:
As a user <br>
I want to ping one of my servers <br>
to check its connectivity.

### 3:
As a user <br>
I want to delete one of my servers <br>
so it doesn't appear anymore on the dashboard

### 4:
As a user <br> 
I want to sort server dashboard by status <br>
so it only displays servers that interest me

### 5:
As a user <br> 
I want to add new server to the dasboard, providing following details: IP, Name, Memory, Type, Status <br>
so that I can follow connectivity of a new server in the dashboard

### 6:
As a user <br> 
I want to print report in xls file that contains all information from dashboard <br>
so that I have all necessary information at hand in seperate Excel file
