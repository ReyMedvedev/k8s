kubectl create ns microservices
kubectl apply -f config.yaml -n microservices
kubectl delete -f config.yaml -n microservices