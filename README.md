## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project illustartes sample static website hosting using nginx on Docker.
* Static Website Credits: andrianvaleanu 
* Repository : [Repo_link](https://github.com/designmodo/html-website-templates) 
	
## Technologies
Project is created with:
* Docker Version:  19.03.13
* Nginx: latest
* Ubuntu: 18.04 LTS
	
## Setup
To run this project, install docker locally on UBUNTU:18.04 LTS:

```
* Clone Repo which creates a directory named Docker-Static-WebHosting. 
* Go Inside the directory and You can have your custom or Sample HTML File
* The Following are Docker Commands to Build and Run a Docker Container to Host Your HTML Page

* This Command Will Build Docker Image  
$ docker build -t staticwebsitehosting . 

* This Command Will Run Docker Container
$  docker run -it --rm -d -p 2020:80 --name website staticwebsitehosting
