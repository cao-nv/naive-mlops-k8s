# Naive MLOps on K8s

## Introduction

We want to build a simple MLOps systems for individuals and small teams for small projects.
The system is built on K8s, and contain following building tool-stack:

* Workflow execution
  * Argo Workflow
* Experiment tracking
  * MLFlow
* Model deployment
  * NVIDIA Triton Inference Server
* Data managment
  * MinIO
  * DVC
* Model monitoring
  * Prometheus
  * Grafana

This repository serve as an example of a simple MLOps pipeline with open-source tools. 