# nginx-nodejs-kubernetes

## commands to follow
```
   minikube start
   kubectl
   kubectl get nodes
   kubectl create -f ingress.yml 
   kubectl create -f nginx-ingress-controller.yml 
   kubectl create -f echoservice.yml 
   kubectl create -f helloworld-v1.yml 
   kubectl create -f helloworld-v2.yml 
   kubectl get pod
   kubectl get pod
   minikube ip
   curl 192.168.99.100
   curl 192.168.99.100 -H 'Host:helloworld-v1.example.com'
   curl 192.168.99.100 -H 'Host:helloworld-v2.example.com'
```
