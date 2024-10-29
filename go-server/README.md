# Deploying a Resilient Go Application on Kubernetes

## Overview

This repository contains resources and configurations for deploying a resilient Go application using DigitalOcean Kubernetes. The tutorial demonstrates how to create a Kubernetes cluster, deploy your Go application, and ensure its resilience through health checks and scaling.

## Prerequisites

Before you begin, ensure you have:

- Basic knowledge of Go programming
- Familiarity with Kubernetes concepts
- `kubectl` installed on your local machine
- Docker installed on your local machine

## Getting Started

1. **Go to given link**

   [digitalocean documentation](https://www.digitalocean.com/community/tutorials/how-to-deploy-resilient-go-app-digitalocean-kubernetes)

## Note that use custom Kubernetes Cluster (minikube, kubeadm)

[check this link for external ip](https://stackoverflow.com/questions/44110876/kubernetes-service-external-ip-pending)

If you are using Minikube, there is a magic command!
```bash
minikube tunnel