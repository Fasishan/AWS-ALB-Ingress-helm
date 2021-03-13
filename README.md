# helm
#Helm Installation in Amazon linux

git clone https://github.com/Fasishan/helm.git
cd helm
mv helm /usr/bin
helm --help


#Installing Ingress through helm
  
  helm repo add nginx-stable https://helm.nginx.com/stable
  helm repo update
  helm install ingress nginx-stable/nginx-ingress -n kube-system
  helm install ingress nginx-stable/nginx-ingress
