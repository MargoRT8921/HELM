```
helm repo add gitlab https://charts.gitlab.io/
helm repo update
helm upgrade --install gitlab gitlab/gitlab --namespace gitlab --timeout 600s -f gitlab_values.yaml
```
