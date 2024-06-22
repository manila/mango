# Mani's Automated deployiNG Orchestrator

> TODO: Find a better acronym

This is an opinionated script for developing and deploying Kustomize templates to a Kubernetes cluster.

## Usage

- `--ingress` hostname that should be added to /etc/hosts by mango 
- `--watch` hotreload when changes are made

`mango run [service_name_folder or cluster_name] --ingress [host_name] --watch`

e.g.

`mango run examples/hello-world --ingress hello-world.manila.internal`

## Installation

1. `brew install minikube fswatch`
2. `git clone git@github.com:manila/mango mango`
3. `mango/install`
