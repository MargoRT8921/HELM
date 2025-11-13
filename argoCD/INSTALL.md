```
helm repo add argo https://argoproj.github.io/argo-helm
helm repo update
helm install argocd argo/argo-cd -f argo_cd_values.yaml -n argocd --create-namespace
```
