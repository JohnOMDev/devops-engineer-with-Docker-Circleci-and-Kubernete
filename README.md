[![CircleCI](https://circleci.com/gh/JohnOMDev/devops-engineer-with-Docker-Circleci-and-Kubernete.svg?style=svg)](https://circleci.com/gh/JohnOMDev/devops-engineer-with-Docker-Circleci-and-Kubernete)

## Project Overview

Serverless project that uses Docker, circleci and Kubernetes skills acquired in the Udacity nanodegree course to operationalize a Machine Learning Microservice API. Project was developed, tested and pushed to production from my local machine

### Project Tasks

Your project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:
* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested


## Setup the Environment
*  Clone the project repository `git clone https://github.com/udacity/DevOps_Microservices.git`
* Create a virtualenv
* Activate a virtual environment
* Installing dependencies via project Makefile : using 'make install'
* Lint Project files with `make lint`

##  Special Libraries must install before starting
* Docker - to Containerize your application
* Hadolint - to Lint the Dockerfile
* Virtual machine
* Kubernetes
* Minikube

### Running the project

1. Standalone:  `python app.py`
2. Run the Docker file:  `./run_docker.sh`
3. Run the Kubernetes file:  `./run_kubernetes.sh`
4. Run the make prediction file  `make_prediction.sh`
5. Run the Upload docker file:  `./upload_docker.sh`
