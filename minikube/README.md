тестове яке частково обісрали<br>
треба дорозібратись та доробити<br>

```
Setup minikube (1 master + 2 workers) and Deploy wordpress + mysql

minikube start --nodes 3 -p projectname
kubectl get nodes
minikube status -p projectname

minikube ip -p projectname
minikube addons disable ingress -p projectname
minikube tunnel -p projectname

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.44.0/deploy/static/provider/cloud/deploy.yaml

kubectl apply -f 0
kubectl apply -f ./
```
