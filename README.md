# Jenkins CI/CD Pipeline with Maven and AWS EC2

## Project Overview

This hands-on project documents the setup and configuration of a CI/CD workflow for a Java application using Jenkins, Maven, GitHub, and AWS EC2.

The project also includes configuration work for Nexus Repository to manage build artifacts.

## Technologies Used

- **Jenkins:** CI/CD automation
- **GitHub:** Source control integration
- **Maven:** Java application build and packaging
- **AWS EC2:** Jenkins server and application deployment environment
- **Linux / Ubuntu:** Server administration
- **SSH:** Secure server connectivity and deployment
- **Nexus Repository:** Artifact repository configuration

## Implementation Steps

1. Created an EC2 instance and installed Jenkins, Java, and Maven.
2. Configured GitHub SSH authentication and Jenkins credentials.
3. Connected the Jenkins job to the GitHub repository.
4. Configured Maven to build and test the Java application.
5. Created a separate EC2 instance for application deployment.
6. Configured secure JAR transfer and remote deployment.
7. Created a Jenkinsfile and configured a pipeline using source control.
8. Set up Nexus Repository using Docker and created a Maven hosted repository.
9. Added Nexus publishing configuration to the Jenkinsfile.

## Key Learning Outcomes

- Jenkins job and pipeline configuration
- GitHub integration with SSH authentication
- Maven build and packaging workflows
- AWS EC2 deployment
- Jenkins credentials and environment variables
- Nexus Repository setup and integration

## Project Documentation

The PDF below contains screenshots and explanations of the implementation steps.

[**View the project documentation**](Jenkins%20maven%20CICD%20ec2.pdf)

## Repository Contents

- `Jenkins maven CICD ec2.pdf` — Screenshot-based project documentation
- `README.md` — Project overview and implementation notes

**Note:** This repository currently contains project documentation rather than the application source code and Jenkinsfile. The final successful Nexus artifact publication is not confirmed in the documentation.

## Author

Sravanth Kantamaneni
