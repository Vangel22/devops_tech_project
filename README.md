# Devops Project - Tasks

1. Dockerize a project
2. Setup a Database
3. Projects for CNCF
    - Vitess - Database
    - Kubernetes - Scheduling and orchestration
    - Prometheus - Monitoring
    - Harbor - Container registry
4. Helm packages for all of the above
5. CI/CD pipeline with Github Actions, Jenkins or Gitlab CI.
6. Step 5 will create new Docker image and will put the new Helm version to Kubernetes.
7. Add loging with Fluentd - https://www.cncf.io/projects/fluentd/
8. Add monitoring with Prometheus - https://www.cncf.io/projects/prometheus/

Make 3-5 pages of docs.


# Starting it up
1. git clone
2. navigate inside devops_tech_project
3. npm install
4. npm start - will start the application locally
5. docker build -t devops-tech-project-local .
6. docker run -d devopps-tech-project-local
7. check http://localhost:3000
8. cd k8s & kubectl apply -f .\devops-tech-project-depl.yaml
9. kubectl get pods - will give you active pods created