# Devops Project - Tasks

1. Dockerize a project
2. Projects for CNCF
    - Kubernetes - Scheduling and orchestration
    - Docker Hub - Container registry
3. Helm packages for all of the above
4. CI/CD pipeline with Github Actions, Jenkins or Gitlab CI.
5. Step 4 will create new Docker image and will put the new Helm version to Kubernetes.

# Starting it up
1. git clone
2. navigate inside devops_tech_project
3. npm install
4. npm start - will start the application locally
5. docker build -t devops-tech-project-local .
6. docker run -d devops-tech-project-local
7. check http://localhost:3000
8. cd k8s & kubectl apply -f .\devops-tech-project-depl.yaml
9. kubectl get pods - will give you active pods created
10. kubectl get deployments - will give you the deployments from the yaml file
11. kubectl get service - will give you the services, here is the react app stored
12. helm create project-helm-chart - creates a helm chart
13. helm install devops-project-chart project-helm-chart/ --values project-helm-chart/values.yaml
14. follow the instructions given by the previous commands and you will have url to check your project in the browser
