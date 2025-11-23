# kojoapp – Simple Helm Chart Demo

This repo contains a basic Helm chart (`kojoapp/`) that deploys an NGINX web server to a Kubernetes cluster.

## Prerequisites

- Kubernetes cluster (e.g. Minikube or Docker Desktop)
- `kubectl` installed and configured
- `helm` installed

## Install

```bash
git clone https://github.com/ideakojo/kojoapp.git
cd kojoapp
helm install kojoapp-release ./kojoapp

