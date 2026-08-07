# Kubernetes Practice

### 📖 About
This repository contains my Kubernetes practice files created while learning Kubernetes from basic to intermediate concepts.

### 📂 Repository Structure

```
kubernetes-Practice/
├── ConfigMaps/
├── Deployments/
├── Pods/
├── Secrets/
├── Services/
├── StatefulSets/
├── Storage/
└── README.md
```

### 🚀 Kubernetes Concepts Covered

- Pod
- Deployment
- Service
- Headless Service
- ConfigMap
- Secret
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)
- Volumes
- StatefulSet

## 📄 Files Included

### Pods
- pod.yaml
- pod-config.yaml
- pod-secret.yaml
- pod-pvc.yaml

### Deployments
- deployment.yaml

### Services
- service.yaml
- headless-service.yaml

### ConfigMaps
- configmap.yaml

### Secrets
- secret.yaml

### Storage
- pv.yaml
- pvc.yaml
- volume.yaml

### StatefulSets
- statefulset.yaml

## ▶️ Apply Resources

Example:

```bash
kubectl apply -f Pods/pod.yaml
```

Deploy a StatefulSet:

```bash
kubectl apply -f StatefulSets/statefulset.yaml
```

## 🛠️ Tools Used

- Kubernetes
- Minikube -- in local
- kubectl
- Docker
- Git
- GitHub

## 🎯 Learning Outcome

Through this repository, I learned:

- Creating Pods and Deployments
- Exposing applications using Services
- Managing ConfigMaps and Secrets
- Working with Persistent Volumes and PVCs
- Deploying Stateful Applications using StatefulSets

---

⭐ If you found this repository useful, feel free to star it!
