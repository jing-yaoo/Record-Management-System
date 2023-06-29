# Record Management System.
Spring Boot based REST-API project.

There are three main subsystems of notes, persons, and items. 
The databases of each can be manipulated through a UI platform.

This API was developed with a layered architectural pattern on top of an 
Model-View Controller(MVC) pattern.

The project uses Spring Web on the server to process and 
reply to REST requests that the client sends using Spring WebFlux.

In order to deploy the application locally, please run both ServerApplication 
and ClientApplication classes simultaneously. 
If it doesn't run on gradle, reconfigure to JDK 17.

Disclaimer:
This code was developed in conjuction with 
the Technical University of Munich's EIST module. I do not own the rights 
to any material found within the repository. Please contact the relevant department
for usage/permission.
