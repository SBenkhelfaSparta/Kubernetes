# Kubernetes
## What is it?
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available.

The name Kubernetes originates from Greek, meaning helmsman or pilot. K8s as an abbreviation results from counting the eight letters between the "K" and the "s". Google open-sourced the Kubernetes project in 2014. Kubernetes combines over 15 years of Google's experience running production workloads at scale with best-of-breed ideas and practices from the community.

## Why use it?
Kubernetes provides you with:

- **Service discovery and load balancing** - Kubernetes can expose a container using the DNS name or using their own IP address. If traffic to a container is high, Kubernetes is able to load balance and distribute the network traffic so that the deployment is stable.
- **Storage orchestration** - Kubernetes allows you to automatically mount a storage system of your choice, such as local storages, public cloud providers, and more.
- **Automated rollouts and rollbacks** - You can describe the desired state for your deployed containers using Kubernetes, and it can change the actual state to the desired state at a controlled rate. For example, you can automate Kubernetes to create new containers for your deployment, remove existing containers and adopt all their resources to the new container.
- **Automatic bin packing** - You provide Kubernetes with a cluster of nodes that it can use to run containerized tasks. You tell Kubernetes how much CPU and memory (RAM) each container needs. Kubernetes can fit containers onto your nodes to make the best use of your resources.
- **Self-healing** - Kubernetes restarts containers that fail, replaces containers, kills containers that don't respond to your user-defined health check, and doesn't advertise them to clients until they are ready to serve.
- **Secret and configuration management** - Kubernetes lets you store and manage sensitive information, such as passwords, OAuth tokens, and SSH keys. You can deploy and update secrets and application configuration without rebuilding your container images, and without exposing secrets in your stack configuration.

## When not to use it
There are plenty of Kubernetes alternatives that can do a better job for certain tasks/projects:
Functions as a Service (FaaS) — Lambda, Google Functions, OpenFaaS, etc.
Platform as a Service (PaaS) — Heroku, Cloud Foundry, Google App Engine, etc.
Containers as a Service (CaaS) — Azure Container Instances, Google Cloud Run, Elastic Container Service, Fargate, DC/OS, etc.
Infrastructure as a Service (IaaS) (VMs) — EC2, GCE, vSphere, etc.
Bare Metal — MaaS, Packet, DIY, etc.

For more information check out this article: https://karlkfi.medium.com/when-not-to-use-kubernetes-ea3b91da3f1f

