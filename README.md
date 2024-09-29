# Kubernetes 101 Series

<p align="center">
  <img src="https://path-to-your-image/kubernetes-logo.png" alt="Kubernetes Logo" width="300px">
</p>

## 🚀 Welcome to Kubernetes 101!

**Kubernetes 101** is a beginner-friendly series designed to help you learn Kubernetes (K8s) from scratch. Whether you're new to container orchestration or familiar with Docker, this repository will guide you through the core concepts of Kubernetes with hands-on exercises and real-world examples.

### 📋 What You Will Learn:
- What Kubernetes is and why container orchestration is important.
- Setting up a local Kubernetes cluster.
- Kubernetes core components: Pods, Deployments, Services, and ConfigMaps.
- Managing containerized applications using Kubernetes.
- Kubernetes networking, storage, and scaling.
- Using Helm for Kubernetes package management.
- Hands-on projects to solidify your learning.

---

## 📚 Prerequisite

Before diving into Kubernetes, it's recommended that you have a basic understanding of containerization and Docker. If you’re new to Docker, check out our **[Docker 101 Series](https://github.com/YOUR_USERNAME/docker-101-series)** to get started with Docker fundamentals before moving on to Kubernetes.

---

## 📚 Table of Contents

1. [Introduction to Kubernetes](#module-1-introduction-to-kubernetes)
2. [Kubernetes Architecture](#module-2-kubernetes-architecture)
3. [Pods, Deployments, and ReplicaSets](#module-3-pods-deployments-and-replicasets)
4. [Services and Networking](#module-4-services-and-networking)
5. [ConfigMaps, Secrets, and Volumes](#module-5-configmaps-secrets-and-volumes)
6. [Scaling and Auto-scaling](#module-6-scaling-and-auto-scaling)
7. [Helm and Kubernetes Package Management](#module-7-helm-and-kubernetes-package-management)
8. [Projects & Real-World Use Cases](#projects--real-world-use-cases)
9. [Contributing](#contributing)

---

## 🧑‍💻 Getting Started

### Prerequisites:
- **Basic Command Line Knowledge**: Some familiarity with the command line and Kubernetes is helpful.
- **Install Kubernetes**: Set up a local Kubernetes environment (using tools like Minikube, Docker Desktop, or KIND) or use a cloud provider’s managed Kubernetes service (e.g., GKE, AKS, EKS).

Once you have your Kubernetes setup ready, verify by running:
```bash
kubectl version --client
```

---

## 📘 Modules Overview

### Module 1: [Introduction to Kubernetes](./01-introduction)
Learn the basics of Kubernetes, the problems it solves, and the core concepts of container orchestration. This module explains why Kubernetes is essential for managing containerized applications at scale.

**Hands-on Exercise**: Set up a local Kubernetes cluster using Minikube or Docker Desktop.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-cluster-diagram.png" alt="Kubernetes Cluster Architecture" width="600px">
</p>
*Example of a simple Kubernetes cluster architecture: Master node, worker nodes, and control plane.*

---

### Module 2: [Kubernetes Architecture](./02-architecture)
Understand the Kubernetes architecture and its core components (Master Node, Worker Nodes, API Server, Controller Manager, etc.). Learn how Kubernetes schedules workloads and manages containerized applications.

**Hands-on Exercise**: Deploy a simple application to a Kubernetes cluster and explore how Kubernetes handles it.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-architecture-diagram.png" alt="Kubernetes Architecture Diagram" width="600px">
</p>
*Diagram showing Kubernetes architecture: Control plane components, nodes, and cluster setup.*

---

### Module 3: [Pods, Deployments, and ReplicaSets](./03-pods-deployments-replicasets)
Learn about the fundamental Kubernetes objects—**Pods**, **Deployments**, and **ReplicaSets**—and how they help manage containerized applications effectively.

**Hands-on Exercise**: Deploy a multi-container application with Pods and manage its lifecycle using Deployments and ReplicaSets.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-pod-lifecycle.png" alt="Kubernetes Pod Lifecycle" width="600px">
</p>
*Illustration showing the lifecycle of a Pod in Kubernetes.*

---

### Module 4: [Services and Networking](./04-services-networking)
Dive into Kubernetes Services and networking models. Learn how to expose your applications, load balance traffic, and manage internal/external communication between Pods.

**Hands-on Exercise**: Create a Kubernetes Service to expose a web application externally.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-services-networking.png" alt="Kubernetes Services Networking" width="600px">
</p>
*Diagram explaining how Services route traffic between Pods and external networks.*

---

### Module 5: [ConfigMaps, Secrets, and Volumes](./05-configmaps-secrets-volumes)
Understand how to manage configuration data using ConfigMaps, handle sensitive information using Secrets, and store data using Volumes in Kubernetes.

**Hands-on Exercise**: Create ConfigMaps and Secrets for a Kubernetes application and mount a Volume for persistent data.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-volumes-diagram.png" alt="Kubernetes Volumes and Persistent Storage" width="600px">
</p>
*Illustration of Kubernetes volumes, showing how data is persisted across Pod restarts.*

---

### Module 6: [Scaling and Auto-scaling](./06-scaling-autoscaling)
Learn about horizontal and vertical scaling in Kubernetes. Understand how to auto-scale applications based on traffic and resource usage.

**Hands-on Exercise**: Implement horizontal pod autoscaling (HPA) for a Kubernetes deployment.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-autoscaling-diagram.png" alt="Kubernetes Auto-scaling Diagram" width="600px">
</p>
*Example of horizontal pod autoscaling based on CPU utilization.*

---

### Module 7: [Helm and Kubernetes Package Management](./07-helm)
Get started with **Helm**, the package manager for Kubernetes. Learn how to use Helm charts to manage complex Kubernetes applications.

**Hands-on Exercise**: Deploy an application using Helm and explore how Helm simplifies Kubernetes deployments.

<p align="center">
  <img src="https://path-to-your-image/helm-kubernetes-diagram.png" alt="Helm Kubernetes Package Management" width="600px">
</p>
*Diagram showing how Helm packages and manages Kubernetes applications.*

---

## 🎯 Projects & Real-World Use Cases

### Project 1: [Deploying a Web Application on Kubernetes](./projects/web-app-kubernetes)
Learn how to deploy a web application (Node.js or Python) on a Kubernetes cluster using Pods, Deployments, and Services. Manage application updates and scaling.

<p align="center">
  <img src="https://path-to-your-image/kubernetes-deployment-project.png" alt="Kubernetes Deployment Project Example" width="600px">
</p>

### Project 2: [Kubernetes with Helm](./projects/helm-application)
Deploy a multi-container application using Helm charts and understand how to manage your application lifecycle through Helm’s version control and rollback features.

---

## 🛠 Contributing

We welcome contributions from the community! Whether it's adding new modules, improving existing content, or fixing issues, your input is valued.

### How to Contribute:
1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Commit your changes and submit a pull request.

For more details, please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

---

## 📞 Support & Questions

If you have any questions or need help, feel free to open an issue or reach out via GitHub Discussions. You can also drop an email to [vijay.saravanan0707@gmail.com](mailto:vijay.saravanan0707@gmail.com?subject=Docker-101).
We’re here to support your Kubernetes learning journey!

---

## ⭐️ Show Your Support

If you find this series helpful, please consider starring the repository! It helps others discover this resource and encourages us to keep improving the content.

---

**Happy Learning! 🚀 ☸️**

