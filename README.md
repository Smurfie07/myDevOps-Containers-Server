# myDevOps-Containers-Server
# 1 A
## Part 1: Application and Container Building
In this part, you will build two containers using Docker, one for the server and another for the client.

Server:
●	Choose an appropriate base image from the Official Images list.
●	Create a Dockerfile for the server container with the following specifications:
●	Use a volume named "servervol" and mount it at "/serverdata" in the container.
●	Install necessary packages and dependencies required for your server application.
●	Write a server application in your preferred language that does the following:
●	Creates a 1KB file with random text data in the "/serverdata" directory.
●	Sends the file and its checksum to the client.
●	Use Docker Compose to define and run the server container.
