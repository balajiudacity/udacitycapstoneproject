In this project, I applied my skills and knowledge which was developed throughout the Cloud DevOps Nanodegree program.

## Project Tasks:

* Working in AWS
* Using Jenkins to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with CloudFormation to deploy clusters
* Building Kubernetes clusters
* Building Docker containers in pipelines

## About Project: 

> I created a CI/CD pipeline for a basic website that deploys to a cluster in AWS EKS which is Blue/Green Deployment.

![img-1](screenshots/Pipeline_implementation_scope_Diagram.png)

## Project Requirement:

> To be able to use this CI/CD pipeline i had setup a EC2 Ubuntu machine with following packages:

* Jenkins
* Blue Ocean Plugin in Jenkins
* Pipeline-AWS Plugin in Jenkins
* Docker
* Pip
* AWS Cli
* Eksctl
* Kubectl

## The files included are:

create-cluster-pipeline - > This is the 1st pipeline to instantiate EKS cluster and node worker group.
container-pipeline -> This contains the 2nd pipeine to implement Docker, blue and green deployment.
