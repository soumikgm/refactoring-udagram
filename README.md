# Udagram Refactoring

Udagram is a simple cloud application that allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice. This version is refactored to completely use microservices and it is my submission for Udacity Cloud Developer Nanodegree. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Setting up the workspace

1. You could start by cloning or downloading a zip file of this repo from the green button on the right side. If you downloaded a zip, then extract it using your favourite tool. If you used git to clone it, you are all set!
2. Open the project in IDE of your choice. Go into the directory udacity-c3-deployment/docker
3. Open the file docker-compose_sample.yaml and add your environment variables. Then rename it to docker-compose.yaml


### Running

In your terminal, navigate to the docker folder by
```
cd udacity-c3-deployment/docker
```
and then run the command
```
docker-compose up
```

### Verifying

Go to localhost:8100/home and see your frontend!

## Prerequisites

* You'll need to install docker https://docs.docker.com/install/.
* You'll need to have an AWS S3 Bucket Enabled
* You'll need to have an AWS RDS set up that has access to your S3 bucket

## My DockerHub profile

* You can find all my public DockerHub Images here - https://hub.docker.com/u/soumikgm
* The images used in this project are
    1. udacity-restapi-user
    2. udacity-restapi-feed
    3. udacity-frontend
    4. reverseproxy

## Built With

* [Ionic](http://www.dropwizard.io/1.0.2/docs/) - Frontend framework
* [Node.js](https://maven.apache.org/) - Backend Framework
* [Postgress](https://rometools.github.io/rome/) - Database
* [Travis-CI](https://travis-ci.org/) - CI Tool
* [Docker](https://www.docker.com/get-started) - Container Creation
* [Kubernetes](https://kubernetes.io/) - Container Orchestration Service
* [AWS](https://aws.amazon.com/) - Cloud Service Provider

## Acknowledgments

* Udacity for providing the starter code
* Juan D (Udacity Cloud Development Technical Mentor) for guiding me through and answering my questions