# MyApp

This is a demo application that showcases a simple Node.js server containerized using Podman and deployed on Kubernetes.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Ussage](#usage)

## Project Overview
MyApp is a basic Node.js application that responds with a simple "Hello, IBMers!" message. The application is containerized using Podman and deployed to a Kubernetes cluster for orchestration.

## Features
- Simple HTTP server built with Node.js
- Containerized using Podman
- Deployed on Kubernetes
- Load-balanced service using Kubernetes Service with type `LoadBalancer`

## Requirements
- [Docker or Podman](https://podman.io/) installed
- [Node.js](https://nodejs.org/) (version 18)
- [Kubernetes](https://kubernetes.io/) with [Minikube](https://minikube.sigs.k8s.io/docs/) for local development
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- A [Docker Hub account](https://hub.docker.com/) (for pushing images)
- [GitHub Actions](https://github.com/features/actions) or any other CI/CD pipeline setup

## Usage
After Cloning using git clone https://github.com/IsmailSabryy/Myapp.git
You can push it to your repo and edit. Any commit will trigger the pipeline.



