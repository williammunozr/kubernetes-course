## How to create a configmap

- kubectl create configmap nginx-config --from-file=reverseproxy.conf
- kubectl get configmap
- kubectl get configmap nginx-config -o yaml
- kubectl create -f nginx.yml
- kubectl create -f nginx-service.yml
- minikube service helloworld-nginx-service --url 
- kubectl exec -i -t helloworld-nginx -c nginx -- bash
