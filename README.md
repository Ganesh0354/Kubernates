# Kubernates
Introduction to Kubernetes
Kubernetes (K8s) is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications. It helps developers efficiently manage microservices-based applications across distributed environments.

1. Kubernetes Basics
1.1 Key Components
Pods: The smallest deployable unit in Kubernetes, containing one or more containers.
Deployments: A controller that manages the rollout and scaling of Pods.
Services: Expose applications to the network inside or outside the cluster.
ConfigMaps & Secrets: Manage environment variables and sensitive information securely.
Ingress: Manages external access to services using a single entry point.

1.2 Kubernetes Architecture
A Kubernetes cluster consists of the following components:

Master Node (Control Plane): Manages cluster state, scheduling, and API requests.
Worker Nodes: Run the application workloads and communicate with the master node.
etcd: A distributed key-value store to maintain cluster state.
Kubelet: An agent that runs on each worker node to ensure the containers are running.
Container Runtime: Kubernetes supports Docker, containerd, and CRI-O to manage containers.

