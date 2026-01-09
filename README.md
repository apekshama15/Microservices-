# Microservices- 
Project - We built a project where the application is divided into small services called microservices, instead of one big application.

Microservices - There are separate services like User Service, Product Service, and Order Service, and each service does only one job.

Each microservice is written using Python Flask, which is simple and lightweight.

Docker - We used Docker to package each service with its code and dependencies so it runs the same everywhere.

Kubernetes - We used Kubernetes (Minikube) to run and manage these containers, handle failures, and keep the services running.

Kubernetes Services are used to expose the microservices so they can be accessed inside and outside the cluster

Scaling - We implemented scaling, so Kubernetes can run multiple copies (pods) of a service when traffic increases.

Using Horizontal Pod Autoscaler, Kubernetes automatically increases or decreases pods based on CPU usage.

Monitoring - We used Prometheus to collect system and application performance data like CPU and memory usage

Visualization - We used Grafana to show these metrics in graphical dashboards, which makes monitoring easy.

Helm - We used Helm to easily install and manage Prometheus and Grafana in Kubernetes.

GitHub - Finally, We uploaded all source code and Kubernetes configuration files to GitHub for version control and sharing.

This project demonstrates a real-world microservices architecture using Docker, Kubernetes, auto-scaling, and monitoring.