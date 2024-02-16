Deploy Application:


```
kubectl apply -f deployment.yaml
```
List Deployments in EKS Cluster:

```
kubectl get deployments
```

Delete Deployment:


```
kubectl delete deployment my-app
```
Scale Deployment:

```
kubectl scale deployment my-app --replicas=5
```
Update Deployment Image:
kubectl set image deployment/my-app my-app=myregistry/my-app:new-tag

Expose Deployment as a Service:

kubectl apply -f service.yaml

Get Services:
```
kubectl get services
```

Create Ingress Resource:

```
kubectl apply -f Ingress.yaml
```


List Ingress Resources:
```
kubectl get ingress
```
