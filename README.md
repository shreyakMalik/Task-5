# DevOps Task 5 — Kubernetes with Minikube

## Overview
This project demonstrates setting up a local Kubernetes cluster using Minikube, deploying an Nginx app, exposing it as a service, and scaling it.

## Steps
1. Installed and started Minikube.
2. Created `deployment.yaml` for Nginx.
3. Created `service.yaml` to expose app via NodePort.
4. Verified pods and services using kubectl.
5. Scaled deployment from 2 to 4 replicas.

## Commands Used
- `minikube start`
- `kubectl apply -f deployment.yaml`
- `kubectl apply -f service.yaml`
- `kubectl get pods`
- `kubectl scale deployment nginx-deployment --replicas=4`
- `kubectl describe deployment nginx-deployment`

## Output
Screenshots included:
- Cluster running
- Pods list
- Service exposed
- Scaled deployment
