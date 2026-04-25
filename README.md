# Kubernetes Resources Repository 🚀

## 📌 Repository Description

This repository contains Kubernetes YAML manifest files for learning, practicing, and deploying core Kubernetes resources including workloads, networking, configuration management, and persistent storage.

Designed for DevOps Engineers, Cloud Engineers, and Kubernetes learners.

---

## 📌 Topics Covered

## Core Resources

- Namespace
- Pods
- Multi-Container Pods
- Labels & Selectors
- Annotations
- Resource Limits & Requests
- Environment Variables

## Configuration Management

- ConfigMap
- Secrets

## Networking

- ClusterIP Service
- NodePort Service
- LoadBalancer Service

## Workload Management

- ReplicaSet
- Deployment
- StatefulSet

## Storage / Volumes

- emptyDir Volume
- hostPath Volume
- AWS EBS Static Provisioning
- StorageClass
- AWS EBS Dynamic Provisioning
- AWS EFS Static Provisioning
- AWS EFS StorageClass
- AWS EFS Dynamic Provisioning

---

## 📂 Repository Structure

```bash
k8-resources/
│── 01-namespace.yaml
│── 02-pod.yaml
│── 03-multi-container.yaml
│── 04-labels.yaml
│── 05-errors.yaml
│── 06-annotations.yaml
│── 07-resources.yaml
│── 08-env.yaml
│── 09-config-map.yaml
│── 10-pod-config.yaml
│── 11-secrets.yaml
│── 12-pod-secret.yaml
│── 13-service.yaml
│── 14-pod-service.yaml
│── 15-service-np.yaml
│── 16-pod-node-port.yaml
│── 17-service-lb.yaml
│── 18-pod-lb.yaml
│── 19-replicaset.yaml
│── 20-deployment.yaml
│── 21-statefulset.yaml
│
└── volumes/
    │── 01-emptyDir.yaml
    │── 02-hostPath.yaml
    │── 03-ebs-static.yaml
    │── 04-sc.yaml
    │── 05-ebs-dynamic.yaml
    │── 06-efs-static.yaml
    │── 07-efs-sc.yaml
    │── 08-efs-dynamic.yaml
```

## 🚀 How to Use

Apply any YAML file:

```bash
kubectl apply -f filename.yaml
```

## Examples:

```bash
kubectl apply -f 20-deployment.yaml
kubectl apply -f volumes/05-ebs-dynamic.yaml
```

## Check resources:

```bash
kubectl get all
kubectl get pv,pvc
```
---

## 🎯 Purpose of This Repository
- Learn Kubernetes practically
- Understand YAML manifests
- Practice storage concepts
- Prepare for DevOps interviews
- Deploy workloads on clusters

---

## 🛠 Tools Used
- Kubernetes
- kubectl
- YAML
- Docker
- AWS EBS / EFS
- Linux

---

## 👨‍💻 Author

Surendra
DevOps Engineer

---

⭐ If you like this project, give it a star.


