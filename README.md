# How to deploy rabbitMQ

First load the configmap using:
```
kubectl create configmap rabbitmqconfig --from-file=./etc/
```

Then the rest can be set up by:
```
kubectl apply -f ./rabbitMQ-deployment.yaml
```
