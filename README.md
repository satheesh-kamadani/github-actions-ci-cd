# GitHub Actions CI/CD Project

This repository contains practical CI/CD workflow examples using GitHub Actions for both Python and Java applications. It demonstrates automated testing, code quality checks, containerization, and deployments to Kubernetes and Docker Swarm.

## Features
### 1. Python CI Pipeline
- Runs automatically on every push
- Installs dependencies
- Executes automated tests using PyTest
- Uses matrix builds for multiple Python versions

### 2. Java CI/CD Pipeline
- Builds Java application using Maven
- Performs static code analysis with SonarQube
- Deploys to Kubernetes cluster
- Demonstrates enterprise-level CI/CD automation

### 3. Kubernetes Deployment Workflow
- Builds Docker images
- Pushes them to a container registry
- Deploys application to Kubernetes using kubectl

### 4. Docker Swarm Deployment Workflow
- Builds and pushes Docker images
- Logs into Docker registry
- Deploys a complete application stack to Docker Swarm