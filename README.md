# ServerDesk-HA-SWARM
Highly available and horizontally scalable web management platform designed to demonstrate modern container orchestration and cloud infrastructure deployment using Docker Swarm on AWS EC2. The application is containerized using Docker and hosted through Apache HTTP Server, with the Docker image distributed through Docker Hub for consistent and portable deployments. The architecture uses a Docker Swarm Manager node and three Worker nodes to provide service replication, fault tolerance, and efficient workload distribution. Docker Swarm’s routing mesh and overlay networking enable communication and traffic distribution across the cluster, while features such as horizontal scaling, automatic task recovery, rolling updates, and service rollback support reliable application operations. The project provides a practical implementation of high-availability web hosting, containerization, distributed infrastructure, and DevOps deployment practices on AWS.

AWS EC2 — Cloud infrastructure
Docker Swarm — Container orchestration
1 Manager Node — Cluster management and scheduling
3 Worker Nodes — Application workload
Apache HTTP Server — Web application hosting
Docker Hub — Container image registry
Overlay Network — Inter-node container communication
Routing Mesh — Traffic distribution across Swarm nodes
Key Features
High Availability
Horizontal Scalability
Container Replication
Automatic Task Recovery
Docker Swarm Routing Mesh
Rolling Updates
Service Rollback
Fault-Tolerant Architecture
Centralized Docker Image Distribution
Technology Stack

AWS EC2 · Docker · Docker Swarm · Apache HTTP Server · Docker Hub · Linux · HTML · Networking

🔄 ServerDesk-HA-SWARM Pipeline

Developer
↓
HTML Web Application
↓
Apache HTTP Server
↓
Dockerfile
↓
Docker Image
↓
Docker Hub
↓
AWS VPC
↓
AWS EC2 Infrastructure
↓
Docker Swarm Manager Node
↓
3 × Docker Swarm Worker Nodes
↓
ServerDesk Replicas
↓
Docker Overlay Network
↓
Swarm Routing Mesh
↓
Users / Web Browser


The ServerDesk application is packaged as a Docker image and published to Docker Hub, making it easy to deploy and customize across different Docker environments.

Repository: naikatharva82/serverdesk-img

License

This project is licensed under the MIT License.
