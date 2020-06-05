## Project 4 - Operationalize a Machine Learning Microservice API
In this project, you will continue your work on operationalizing microservices by deploying an elastic and fault-tolerant Machine Learning inference API using Kubernetes. You’ll configure this microservice to be highly available by using Kubernetes best practices. You will validate your design by load testing the service and verifying the application architecture performs as designed.

You are given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on.

### Project Tasks

- Test your project code using linting
- Complete a Dockerfile to containerize this application
- Deploy your containerized application using Docker and make a prediction
- Improve the log statements in the source code for this application
- Configure Kubernetes and create a Kubernetes cluster
- Deploy a container using Kubernetes and make a prediction
- Create a pipeline using CircleCI