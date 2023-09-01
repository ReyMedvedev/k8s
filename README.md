```
kubectl cluster-info
kubectl get nodes
kubectl get all -n <namespace>
kubectl get <ресурс> <ім'я_ресурсу> -n <namespace>
kubectl describe <ресурс> <ім'я_ресурсу> -n <namespace>
kubectl apply -f <файл.yaml>
kubectl delete <ресурс> <ім'я_ресурсу> -n <namespace>
kubectl exec -it <ім'я_поду> -n <namespace> -- <команда>
kubectl logs <ім'я_поду> -n <namespace>
kubectl create namespace <namespace>
kubectl config set-context --current --namespace=<namespace>
kubectl cp <namespace>/<под>:/<віддалений_шлях_файлу> <локальний_шлях>
kubectl cp <локальний_файл> <namespace>/<под>:<віддалений_шлях_файлу>
kubectl get namespaces
kubectl config view
```
```
helm init
helm repo update
helm search repo <назва_чарту>
helm install <назва_встановлення> <назва_чарту>
helm ls
helm get values <назва_встановлення>
helm upgrade <назва_встановлення> <назва_чарту>
helm delete <назва_встановлення>
helm get history <назва_встановлення>
helm show chart <назва_чарту>
helm show readme <назва_чарту>
helm show values <назва_чарту>
```