# Ingress Controller

- kubectl create -f ingress.yml
- kubectl create -f nginx-ingress-controller.yml
- kubectl create -f echoservice.yml
- kubectl create -f helloworld-v1.yml
- kubectl create -f helloworld-v2.yml

## Validating Ingress Controller

- minikube ip
- curl 192.168.64.2 -H 'Host: helloworld-v1.example.com'
- curl 192.168.64.2 -H 'Host: helloworld-v2.example.com'

