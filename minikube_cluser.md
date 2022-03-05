# Minikube cluster

## Running with configurations

Apply the configurations for service / deployment / pods.

```
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongo-express.yaml ## create internal and external service for mongo-express
```

Verify that pods are running.

```
kubectl get pod  ## verify that pods are running
kubectl logs mongo-express-68c4748bd6-9hd44  ## see the logs for mongo-express pod
```

External web service for mongo database admin:

```
minikube service mongodb-express-service  ## assign external service a public IP address
```
