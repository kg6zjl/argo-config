# argo-config
Config for ArgoCD

Manual steps:
```
kubectl create namespace argocd

kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

kubectl apply -f argocd-self-management.yaml
```
