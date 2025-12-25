
Deploy to Kubernetes

1️⃣ Start Cluster
minikube start

2️⃣ Enable Ingress
minikube addons enable ingress

3️⃣ Apply Manifests
kubectl apply -f k8s/

4️⃣ Access App
minikube ip


Add to /etc/hosts:

<minikube-ip> nginx.local


Open:

http://nginx.local
