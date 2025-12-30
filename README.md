
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
if windows do C:/Windows/System32/etc/hosts - Run as administrator in notepad and then edit

<minikube-ip> nginx.local


Open:

http://nginx.local

Use minikube tunnel - run this command as administrator

If it fails , then again edit hosts file as given below

127.0.0.1 nginx.local
