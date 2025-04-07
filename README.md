# cicd-python-aws-example

This repository contains a skeleton code and configuration files necessary for deploying a basic Django application using an automated CI/CD pipeline into AWS ECS.

## Folder Structure
- `.github/workflows/:` This directory houses the GitHub Actions workflow files defining the CI/CD pipeline.
- `mydemo/:` Contains the main code files for the application.
  
## Pipeline Overview
The pipeline is triggered by events like code pushes or pull requests. It automatically builds, tests, and deploys the Django application into Amazon ECS. The process includes infrastructure configuration, code deployment, and automated testing.

## Get Started
1. Create a python virtual environment to install the dependences using:
```bash
  pip install -r requirements.txt
```
2. Run locally the server:
```bash
  python manage.py runserver
```
3. Configure the pipeline by modifying the workflows in the .github/workflows directory to match your specific deployment requirements.
4. Create the github secrets defined in the github action file.
   
Feel free to explore the repository for more details on the pipeline setup and configuration.