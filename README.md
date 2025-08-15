# ci-cd-webapp-jenkins-docker-k8s
End-to-end CI/CD pipeline using Jenkins, Docker, Kubernetes, and GitHub Actions
# CI/CD Pipeline for Web Applications

This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline for web applications using Jenkins, Docker, Kubernetes, and GitHub Actions.

## Technologies Used

- Jenkins
- Docker
- Kubernetes
- GitHub Actions

## Project Highlights

- Designed a Jenkins pipeline to automate build-test-deploy workflows.
- Used Docker to containerize the application.
- Deployed containers to Kubernetes with health checks and rolling updates.
- Integrated GitHub Actions for lightweight CI automation.

## Folder Structure

ci-cd-webapp-jenkins-docker-k8s/ 
├── jenkins/ 
│ └── Jenkinsfile 
├── docker/ 
│ └── Dockerfile 
├── k8s/ 
│ └── deployment.yaml 
├── .github/ 
│ └── workflows/ 
│ └── ci.yml 
├── .gitignore 
└── README.md



## How to Use

1. Clone the repository:
   git clone https://github.com/dhanushvaddi/ci-cd-webapp-jenkins-docker-k8s.git

2. Build and push Docker image:
   docker build -t your-dockerhub-username/mywebapp .
   docker push your-dockerhub-username/mywebapp

3. Deploy to Kubernetes:
   kubectl apply -f k8s/deployment.yaml

4. Configure Jenkins pipeline using Jenkinsfile

## Author

Dhanush R  
DevOps Engineer | CI/CD | Cloud | Containers  
LinkedIn: https://linkedin.com/in/dhanushr
