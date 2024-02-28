minikube start
minikube addons enable ingress
minikube dashboard
kubectl apply -f manifest.yaml
kubectl get ingress -n wordpress-namespace
minikube tunnel
minikube delete --all
