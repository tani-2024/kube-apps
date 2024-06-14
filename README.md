# Containerized Multi-Tier Web Application Stack on Kubernetes

This project aims to containerize a multi-tier web application stack on Kubernetes.
# Requirements
1. High availability
2. Fault tolerance
3. Easy scalability
4. Platform independence
5. Portability and Flexibility

# Steps to be Followed

1. **Create Kops Kubernetes Cluster**: Set up a Kubernetes cluster using Kops to provide the infrastructure for deploying the application.

2. **Containerize the Application**: Dockerize the application components to make them easily deployable and scalable within the Kubernetes environment.

3. **Create EBS Volume for DB Pod**: Set up an EBS volume to provide persistent storage for the database pod, ensuring data persistence and fault tolerance.

4. **Write Definitions.yaml Files**: Define Kubernetes resources such as Deployments, Services, Secrets, and Volumes in YAML files to configure and deploy the application stack.
5.  **Run kubectl apply**: Finally deploy your definitions files on Kubernetes cluster.

## Installation and Usage

Include any installation instructions or guidelines for deploying the application stack on Kubernetes. Provide instructions on how to scale the application, manage resources, and access the deployed services.

