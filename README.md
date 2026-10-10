# Jenkins CI/CD Pipeline Automation with Maven and AWS EC2

## Project Overview
This project demonstrates a CI/CD pipeline for building, testing, packaging, and deploying a Java application using Jenkins, Maven, GitHub, and AWS EC2.

## Technologies Used
- Jenkins – CI/CD pipeline automation
- GitHub – Source code management
- Maven – Java application build and packaging
- AWS EC2 – Jenkins and application server environments
- SSH – Secure server connectivity
- Nexus Repository – Artifact management

## Project Workflow
1. Created and configured a Jenkins server on AWS EC2.
2. Connected Jenkins to GitHub using SSH credentials.
3. Configured Maven to build and test the Java application.
4. Packaged the application into a JAR file.
5. Configured secure deployment from Jenkins to an application EC2 instance.
6. Configured Nexus Repository and added an artifact-publishing stage to the Jenkinsfile.

## Key Learning Outcomes
- Jenkins job and pipeline configuration
- GitHub integration and SSH authentication
- Maven build and packaging
- Automated deployment to AWS EC2
- Jenkins credentials and environment variables
- Nexus Repository integration

## Project Documentation
The PDF in this repository contains screenshots and step-by-step explanations of the project implementation.

**Documentation:** [Jenkins Maven CI/CD EC2 PDF](Jenkins%20maven%20CICD%20ec2.pdf)

## Author
Sravanth Kantamaneni
