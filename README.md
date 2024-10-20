# Demo Project:
Complete CI/CD Pipeline with EKS and AWS ECR

# Technologies used:
Kubernetes, Jenkins, AWS EKS, AWS ECR, Java, Maven, Linux, Docker, Git

# Project Description:
Create private AWS ECR Docker repository
Adjust Jenkinsfile to build and push Docker Image to AWS ECR
Integrate deploying to K8s cluster in the CI/CD pipeline from AWS ECR private registry
So the complete CI/CD project we build has the following configuration:
CI step: Increment version
a.
CI step: Build artifact for Java Maven application
b.
CI step: Build and push Docker image to AWS ECR
c.
CD step: Deploy new application version t
