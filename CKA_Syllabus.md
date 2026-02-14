# 📘 Certified Kubernetes Administrator (CKA) – Official Syllabus

This repository documents the **official and complete syllabus** for the  
**Certified Kubernetes Administrator (CKA)** certification, published by the  
**Linux Foundation** in collaboration with the **Cloud Native Computing Foundation (CNCF)**.

The CKA exam is **100% performance-based**, conducted on a live Kubernetes cluster.

---

## 🧩 Exam Overview

- **Certification**: Certified Kubernetes Administrator (CKA)
- **Exam Type**: Hands-on / Practical
- **Duration**: ~2 hours
- **Passing Score**: As defined by Linux Foundation
- **Documentation Allowed**: Official Kubernetes documentation
- **Kubernetes Version**: Aligned with current exam version (e.g., v1.34)

---

## 📌 Official Exam Domains & Weightage

| Domain | Weight |
|------|--------|
| Cluster Architecture, Installation & Configuration | 25% |
| Workloads & Scheduling | 15% |
| Services & Networking | 20% |
| Storage | 10% |
| Troubleshooting | 30% |

---

## 1️⃣ Cluster Architecture, Installation & Configuration (25%)

Candidates must be able to:

### Kubernetes Architecture
- Understand Kubernetes cluster architecture
- Understand control plane components:
  - kube-apiserver
  - kube-controller-manager
  - kube-scheduler
  - etcd
- Understand worker node components:
  - kubelet
  - kube-proxy
  - container runtime

### Cluster Setup & Management
- Design and configure Kubernetes clusters
- Install Kubernetes using `kubeadm`
- Configure a **High Availability (HA)** control plane
- Upgrade Kubernetes clusters (control plane and worker nodes)
- Backup and restore `etcd`
- Manage Kubernetes certificates

### Security & Access
- Configure and manage RBAC:
  - Roles
  - ClusterRoles
  - RoleBindings
  - ClusterRoleBindings
  - ServiceAccounts

### Extensions
- Understand and manage:
  - Custom Resource Definitions (CRDs)
  - Admission Controllers
  - Cluster extensions

---

## 2️⃣ Workloads & Scheduling (15%)

Candidates must be able to:

### Workload Management
- Deploy and manage:
  - Pods
  - Deployments
  - ReplicaSets
  - StatefulSets
  - DaemonSets
  - Jobs
  - CronJobs

### Updates & Scaling
- Perform rolling updates and rollbacks
- Scale workloads manually

### Configuration & Resources
- Configure and use:
  - ConfigMaps
  - Secrets
- Understand and configure:
  - Resource requests
  - Resource limits

### Scheduling
- Configure scheduling using:
  - Node selectors
  - Node affinity / anti-affinity
  - Taints and tolerations
- Understand autoscaling concepts (HPA basics)

---

## 3️⃣ Services & Networking (20%)

Candidates must be able to:

### Networking Fundamentals
- Understand Kubernetes networking model
- Configure Pod-to-Pod communication

### Services
- Create and manage Services:
  - ClusterIP
  - NodePort
  - LoadBalancer

### Ingress & DNS
- Understand and configure:
  - Ingress
  - Ingress Controllers
- Configure and troubleshoot CoreDNS

### Network Security
- Implement and manage Network Policies
- Understand CNI concepts (operational level)

---

## 4️⃣ Storage (10%)

Candidates must be able to:

### Storage Concepts
- Understand Kubernetes storage architecture

### Persistent Storage
- Configure and manage:
  - PersistentVolumes (PV)
  - PersistentVolumeClaims (PVC)

### Storage Classes
- Understand:
  - Access modes
  - Reclaim policies
- Configure:
  - StorageClasses
  - Dynamic volume provisioning

### Workload Integration
- Attach and manage storage for Pods and workloads

---

## 5️⃣ Troubleshooting (30%)

Candidates must be able to:

### Application Troubleshooting
- Troubleshoot Pods:
  - Pending
  - CrashLoopBackOff
  - ImagePullBackOff
- Debug application failures

### Networking & Services
- Troubleshoot Service connectivity issues
- Debug DNS and network-related problems

### Node & Cluster Issues
- Troubleshoot node failures
- Troubleshoot control plane components

### Observability
- Analyze:
  - Pod logs
  - Node logs
  - Control plane logs
- Use events and metrics for debugging
- Identify and fix misconfigurations efficiently

---

## 🧠 Important Notes

- This syllabus is **official and authoritative**
- No multiple-choice questions
- Speed, accuracy, and hands-on skill matter
- Practice directly on Kubernetes clusters

---
