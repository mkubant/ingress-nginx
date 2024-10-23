# ingress-nginx
## nasazení ingress-nginx kustomize do ArgoCD
```bash
kubectl apply -f generator
```
- vytvoří AplicationSet `nginx`
- vytvoří namespace `nginx`
- vytvoří DaemonSet `nginx`
- vytvoří další nezbytné komponenty
- vystaví se port `32080` a `32443`
