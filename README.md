# KubePlatform

Create production-ready Development Platform for Kubernetes. It contains tools for:

- Monitoring, Alerting, Logging
- Ingress based adding of DNS entries and TLS Certificates
- Oauth based authentication
- CI/CD

In detail - installed tools are:

- nginx Ingress Controller
- Prometheus (+ node-exporter), Grafana, Alert Manager, kube-state-metrics, etc.
- EFK Stack
- External DNS
- cert-manager
- oauth2-proxy
- keycloak
- argo Workflow, argo-events

Visit the [KubePlatform component description](https://kube-platform.github.io/docs/components/) for more insight.

## Precondition
- [kustomize](https://github.com/kubernetes-sigs/kustomize/releases) is needed for the installation
- A DigitialOcean Kubernetes Cluster with at least 3 nodes with a node plan of ```Includes: 8 GB Memory / 4 vCPUs``` is required

## Installation
The tutorial [Getting Started on GKE](https://kube-platform.github.io/docs/tutorial/) is a step-by-step walkthrough for installing KubePlatform on GKE/GCP in 10 minutes.
