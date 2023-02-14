![badge](https://github.com/chloekang234/microservices-TodoList-in-Flask/actions/workflows/main.yml/badge.svg)

# Microservice ToDo List App in Flask API

## Objectvices of Project
Todo List app that can track completed and incomplete tasks using Flask API. Flask-SQLAlchemy extension was used to utilize database. New task can be added through Add item interface. To update incomplete items to completed items, **Mark As Complete** button is used. Items can be deleted by **Delete** button.

![UI](https://github.com/chloekang234/microservices-TodoList-in-Flask/blob/main/src/UI%20screen.png)

Live Website link: https://j7mxk3vtmm.us-east-1.awsapprunner.com

## Project Structure
![Project Structure](https://github.com/chloekang234/microservices-TodoList-in-Flask/blob/main/src/Project%20Structure.png)


## Running the web application locally:

Step 1: Clone github repository
`git clone https://github.com/chloekang234/microservices-TodoList-in-Flask.git`

Step 2: Change location to the cloned repository
`cd microservices-TodoList-in-Flask`

Step 3: Activate virtual environment
`source virt/bin/activate`

Step 4: Install all package dependencies
`make install`

Step 5: Start Docker Desktop on local computer to use Docker and Create a docker image based on Dockerfile
`docker build --tag=<tag_name>`

Step 6: List created docker images to get image ID
`docker image ls`

Step 7: Run a docker to run the app locally
`docker run -p 127.0.0.1:8080:8080 <image ID>`


## Set up the project from scratch

**Step 1**: Create virtual environment

A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them. It can be created by following commands:
`python3 -m venv ~/<your-project-env>`

To activate the created virtual environment,
`Source <your-project-env>/bin/activate`

**Step 2**: Create source codes including requirements.txt and Makefile
Create source code such as app.py and HTML/CSS including requirements.txt and Makefile. requirements.txt is a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project. Makefile is a set of commands (similar to terminal commands) with variable names and targets to create object file and to remove them. It can increase effiency during development.

To make a new file, the following command is used.

`touch <filename>`

e.g. `touch requirements.txt`


**Step 3**: Configure Build System to Deploy changes

 **Use AWS App Runner to deploy web-app**: 

AWS App Runner is a fully managed container application service that lets you build, deploy, and run containerized web applications and API services without prior infrastructure or container experience. To deploy web applications, the following step needed.





