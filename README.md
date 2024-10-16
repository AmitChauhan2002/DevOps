# DevOps-CICD

This repository documents the steps to set up a CI/CD pipeline for a simple Java project, covering the entire process from Jenkins setup to deploying on Kubernetes.

## Setting up Jenkins and Plugins for the CI/CD Pipeline

Navigate to the `Jenkins` folder and follow the instructions in the specified order:

1. **Jenkins Instructions:**
   - Set up an EC2 instance and install Java and Jenkins.

2. **Maven Instructions:**
   - Install Maven to use as a build tool in the pipeline.

3. **Git Instructions:**
   - Install and integrate the Git plugin to enable automatic updates after each push.

## Integrating a Tomcat Server

- Navigate to the `Tomcat` folder and follow the instructions to integrate the Tomcat server.

## Deploying into a Docker Container using Jenkins

- Go to the `Docker` folder and follow the provided instructions for deploying your application into a Docker container via Jenkins.

## Using Ansible to Automate Deployment into the Docker Container

- Navigate to the `Ansible` folder and follow the instructions to automate the deployment process with Ansible.

## Replacing the Docker Host with Kubernetes

- Navigate to the `Kubernetes` folder and follow the instructions for setting up Kubernetes.

1. **Kubernetes Instructions:**
   - Set up Kubernetes on a new EC2 instance.

## Jenkins and Ansible Integration Instructions

- Follow the provided integration instructions for setting up Jenkins and Ansible for deployment.

---

This guide provides step-by-step instructions to set up a robust CI/CD pipeline, leveraging various DevOps tools and platforms.

