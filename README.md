Cài đặt argocd
```
cd argocd
helm install argocd argo/argo-cd --version 10.10.5 -n argocd --create-namespace -f custom-values.yaml
```

Cài đặt bootstrap
```
cd ..
kubectl apply -f bootstrap.yaml
```
