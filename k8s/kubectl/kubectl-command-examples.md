
List API versions compatible with your cluster version.

```bash
kubectl api-versions
```

Imperative command to run a Pod 

```bash
kubectl run frontend --image=nginx:1.24.0 --port=80
```

Edit the configuration of a Pod

```bash
kubectl edit pod frontend
```

Patch a Pod to change the version 

```bash
kubectl patch pod frontend -p '{"spec": {"containers": [{"name": "frontend", "image": "nginx:1.25.1"}]}}'
```

Delete a Pod now without waiting for the grace period (not recommended for production).

```bash
kubectl delete pod nginx --now
```

Create a manifest using dry run.

```bash
kubectl run frontend --image=nginx:1.25.1 --port=80 -o yaml --dry-run=client > pod.yaml
# make your edits to pod.yaml
kubectl apply -f pod.yaml
```



