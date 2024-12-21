Agenda: Building a springbootwebtutorial.zip, spring application

### Class 2.1:

In Spring initializr
config:
	Project:
		Maven
	Language:
		Java
	Spring Boot:
		3.3.0 # Snapshots aren't stable always
	Project Metadata:
		Group: 
			com.codingshuttle.springbootwebtutorial
		Artifact:
			springbootwebtutorial
		Name:
			Spring Boot Web Tutorial
		Description:
			Demo project for Spring Boot and Spring Boot Web Tutorial 
		Package name:
			com.codingshuttle.springbootwebtutorial.springbootwebtutorial
			# Group.Artifact 
		Packaging:
			Jar
		Java:
			22

Dependencies:
	Spring Web 

Note:
	spring-boot-starter-web contains the following dependencies:
	spring-boot-starter 
	jackson
	spring-core 
	spring-mvc
	spring-boot-starter-tomcat

It can be viewed by going to file definition

Write a clear Notes on architecture
	1. MVC
	2. Layered Architecture

Why to use MVC Architecture (write in detail)
	1. Separation of Concerns
	2. Reusability
	3. Testability
	4. Scalability

Spring Boot Web Project Structure
	client
	Controller (DTOs, client Data. i.e. Controller Services communicates through DTOs)
	Service
	repository (Entity, DB Data. i.e. Repository & Services communicates through Entity)
	Actual Database

### Class 2.2 
	It's a job of dispatcher servlet that maps end point to controller.
	

2.7. Look into Exception handler topics.

2.9. Complete StreamAPI.zip project.

# This repo contains 2 projects
## 01-SpringBootWebTutorial
## 02-StreamAPI

## Details are provided in each ReadMe File of the project