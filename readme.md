# Pushing Node or Java App image to Amazon Elastic Container Registry

## Overview

This lab learner's ability to containerize a new or existing node or java application and deploy the container image to Amazon Elastic Container Registry using GitHub Actions Pipeline.

## Tasks:

- Prepare your application by writing a dockerfile and other relevant files to enable building a container image of your application.

- Configure a GitHub Actions workflow that triggers on every push to your repository. The workflow should:

  - Build the Docker image of your application.
  - Tag the Docker image using the format: yourfullname_appname
  - Push the Docker image to your public ECR repository.

## Screenshots

### ECR Public Registries

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/e5d14aa3-7b05-4fbe-be57-2ca75ff1ffbf" />

### Github Actions Workflow

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/cfcd14d5-3cfd-4ce7-b657-db1292d959bd" />

### Pushed Images

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/a8d59dd2-2aaa-4a59-b3c4-9455c604b207" />

### Pushed Image Details

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/975033c6-7282-419b-9c58-4ca2d83cb104" />
