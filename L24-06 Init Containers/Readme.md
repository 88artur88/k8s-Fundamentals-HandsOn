Init container:

## Create the deployment
```shell
kubectl apply -f myapp.yaml
kubectl get pods
kubectl exec -it init-demo -- /bin/bash
```
