# fib-kubernetes-tutorial

# kubectl command 


### remove

kubectl delete -f [pods|services|deployments|secrets] [name]

### log

kubectl logs [name]

### get command
kubectl get pods
kubectl get services
kubectl get deployments
kubectl get secrets

### create secret 
kubectl create secret generic [name] --from-literal [key=values]