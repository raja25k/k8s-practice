# Kubernetes Nginx ConfigMap Demo

A beginner-friendly Kubernetes project that deploys Nginx using:

- ✅ Namespace isolation
- ✅ Persistent Volume Claim (PVC)
- ✅ Deployment and Service
- ✅ Ingress with hostname routing

## 🧪 Prerequisites

- Minikube + kubectl
- Ingress enabled: `minikube addons enable ingress`

## 🚀 Apply Resources

```bash
kubectl apply -f namespace.yaml
kubectl apply -f volume.yml
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
kubectl apply -f nginx-ingress.yaml
```

##🌐 Access App
- Add to your /etc/hosts: <minikube-ip> nginx.local
- Then visit: http://nginx.local in browser


##📂 Project Goal
- Understand how Kubernetes components like Namespace, PVC, Ingress, and ConfigMap work together to deploy real apps
