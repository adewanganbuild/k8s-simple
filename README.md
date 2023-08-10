This is a project setup from the udemy course: https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/learn/lecture/11482930#overview

Configure the pod and Nodeport using:
kubectl apply -f client-pod.yaml
kubectl apply -f client-node-port.yaml

kubectl get pods
kubectl get services
kubectl ip
