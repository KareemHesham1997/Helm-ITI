# Helm-ITI
To start the project run this commands
```

helm install redis redis-chart/

helm install python python-chart/
```
Check for running pods
```
kubectl get pods 
```
To access the app type the nodeport ip with the port
