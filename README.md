# kube-directory

A containerized employee search application deployed on Google Kubernetes Engine (GKE) using Docker, Kubernetes, and Google Cloud infrastructure.

The project demonstrates how to deploy a web application with external traffic routing, internal service discovery, persistent database storage, and application-level redundancy.

## Features
* Search employee records by name or position.
* Containerized application and database
* Route external traffic through a LoadBalancer and NGINX reverse proxy.
* Kubernetes Services for external access and internal service discovery
* Persist PostgreSQL data beyond database Pod recreation.
* Application replicas distributed across worker nodes using pod anti-affinity
* Kubernetes Secrets for database credentials

**Tech Stack:**  Node.js · PostgreSQL · Docker · Kubernetes · GKE · NGINX · Google Cloud Build · Google Container Registry
