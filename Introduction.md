# Virtual Machines
VMs provide hardware virtualization. The compute and memory resources of a machine such as CPU, RAM are divided into chunks and each chunk can be utilized for a different task rather than installing multiple machines for multiple tasks. Each chunk operates on it's own (guest) OS different from the host OS.

# Containers
These are light weight alternatives to VMs. These provide virtualization on the entire OS. They operate on the host OS.

## Docker
It is a container runtime tech. It allows to build, test and deploy applications.

# Kubernetes
Used to create, scale and manage containers.

smallest unit - pod
pods group similar containers together and store inside it. All containers inside a kubernetes pod have same IP address.

Cublets store multiple pods within them. 

Deployments are used to manage pods.

Services provide IP address and DNS address and so pods can be accessed from within the kubernetes cluster.

However, if the pod must be accessed from outside world, it must be connected to Ingress or attach a LoadBalancer to the service itself.



