# helm3
- $:~/helm3$ curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
- $:~/helm3$ chmod 700 get_helm.sh 
- $:~/helm3$ sudo apt install openssl
- $~/helm3$ ./get_helm.sh
- $~/helm3$ helm version
- $~/helm3$ helm install svcwordpress bitnami/wordpress -f
- $~/helm3$ minikube service svc1wordpress --url

