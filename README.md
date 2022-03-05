# oncok8s

## About

Objective: Prototype a setup for containerized application in a cluster for distributed image storage and analysis

### Introduction
With the transition from monolith to microservices in the computing domain, there is increased use of containers. 

The application to cancer biology arises in that there is an unmet need in using orchestration tools for image analysis for pathological specimens. 
While it is possible to run distributed applications with other infrastructure such as AWS / your own setup, we built the infrastructure with Kubernetes due to ease of setup (e.g. default self-healing, smart scheduling) and customizability.

## Setup

* Virtualization: Docker
* Cluster setup: Prototype / cluster for testing purpose: Minikube (1-node K8s cluster locally)
* Machine tested on: Macbook Air (mac OSX - apple M1 chip)

### Architecture

#### Pods: 
- mongo
- mongo-express 

#### Deployments: 
- mongo
- mongo-express 

#### Services:
- mongo
- mongo-express 


#### Database

* Db - MongoDB: used docker image https://hub.docker.com/_/mongo
* Web - Mongo-express: used docker image https://hub.docker.com/_/mongo-express

