# 🚀 Kubernetes Monitoring Project with Prometheus & Grafana

## 📌 Project Overview

This project demonstrates the deployment of a containerized Flask application on Kubernetes using Minikube and Docker. It includes a complete monitoring stack with Prometheus and Grafana for real-time observability, along with load testing and validation to ensure application reliability.

---

## 🎯 Objectives

* Containerize a Flask application using Docker
* Deploy the application on Kubernetes
* Expose the application using Kubernetes Services
* Monitor application and cluster metrics with Prometheus
* Visualize metrics through Grafana dashboards
* Perform load testing and performance validation
* Deploy and manage the environment on AWS EC2

---

## 🛠️ Technologies Used

* Python
* Flask
* Docker
* Kubernetes
* Minikube
* Prometheus
* Grafana
* AWS EC2
* Apache Benchmark (ab)
* Linux (Ubuntu)

---

## 📂 Project Structure

```text
kubernetes-monitoring-project/
│
├── app.py
├── Dockerfile
├── deployment.yaml
├── service.yaml
├── requirements.txt
├── README.md
└── screenshots/
```

---

## ⚙️ Application Deployment Workflow

1. Developed a Flask web application.
2. Created a Docker image for the application.
3. Deployed the application on Kubernetes using Deployment and Service manifests.
4. Configured NodePort service for external access.
5. Installed Prometheus and Grafana for monitoring.
6. Created dashboards to visualize Kubernetes metrics.
7. Performed load testing and validated application performance.

---

## 📊 Monitoring & Observability

### Prometheus

* Collected Kubernetes cluster metrics
* Monitored application availability
* Tracked system performance

### Grafana

* Created monitoring dashboards
* Visualized resource usage
* Displayed Kubernetes health metrics
* Monitored service status in real time

---

## 🧪 Load Testing

Load testing was performed using Apache Benchmark (ab).

Example:

```bash
ab -n 1000 -c 50 http://<application-url>/
```

### Validation Metrics

* Requests per second
* Response time
* Failed requests
* Application availability
* Pod health status

---

## ☁️ AWS Deployment

The entire project was deployed on an AWS EC2 instance running Ubuntu.

### Services Used

* EC2
* Docker
* Kubernetes (Minikube)
* Prometheus
* Grafana

---


---

## ✅ Project Outcomes

* Successfully deployed a containerized application on Kubernetes.
* Implemented real-time monitoring using Prometheus and Grafana.
* Validated application performance through load testing.
* Demonstrated cloud deployment and container orchestration skills.
* Built a production-style monitoring and observability environment.

---

## 👩‍💻 Author

**Priyanshi Patel**
B.Sc. Information Technology
Aspiring Data Analyst | Data Scientist | Cloud & DevOps Enthusiast
