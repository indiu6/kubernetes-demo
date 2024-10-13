# kubernetes-demo

### For K8s Secret

```
echo -n mongouser | base64
echo -n mongopassword | base64
```

## Introduction to Kubernetes:

### Kubernetes is defined as a container orchestration platform that automates the deployment, scaling, and management of containerized applications.

### It helps manage containerized applications across a cluster of nodes.

- Basic Kubernetes Components:

> Pod: The smallest deployable unit, which can run one or more containers.

> Node: A worker machine (physical or virtual) in the Kubernetes cluster that runs pods.

> Deployment: Manages a set of identical pods and ensures they are running.

> Service: Provides a stable endpoint to expose pods and enables communication both internally within the cluster and externally.

- Set up a local Kubernetes environment using Minikube.

> Deploying a simple Nginx application using YAML configurations, scaling deployments, and accessing the deployed application via services.

> The use of kubectl commands to manage and inspect Kubernetes resources (like checking pod statuses and accessing logs).

- Advanced Concepts:

> Scaling, networking, and handling persistent storage with Kubernetes.

> The use of ConfigMaps for handling configuration data and Secrets for sensitive information.
