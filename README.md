# Microservices-and-CI-CD-Pipeline-Builder
AWS Microservices project using Docker, Amazon ECR, ECS, ALB, CodeCommit, CodePipeline, and CodeDeploy.

# AWS Microservices Project

## Overview

This project demonstrates the deployment of a microservices-based application using AWS and Docker.

The application consists of two microservices:

* Customer Microservice
* Employee Microservice

## AWS Services Used

* AWS Cloud9
* AWS CodeCommit
* Amazon ECR
* Amazon ECS
* Application Load Balancer
* AWS CodePipeline
* AWS CodeDeploy
* AWS CloudFormation
* Amazon RDS

## Implementation

1. The application was divided into Customer and Employee microservices.
2. Docker was used to containerize the microservices.
3. Docker images were pushed to Amazon ECR.
4. Amazon ECS was used to run the containers.
5. Target groups and an Application Load Balancer were configured.
6. AWS CodeCommit was used for source-code management.
7. AWS CodePipeline was configured for CI/CD.
8. AWS CodeDeploy was used to deploy the updated ECS services.
9. Amazon RDS was used for the supplier database.
10. The deployed application and supplier management functionality were verified.

## Result

The Customer and Employee microservices were successfully containerized and deployed on AWS with a CI/CD workflow using CodeCommit, CodePipeline, and CodeDeploy.
