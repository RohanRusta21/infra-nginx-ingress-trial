# infra-nginx-ingress-trial

```bash

helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx



helm repo update



helm upgrade --install ingress-nginx ingress-nginx \
> --repo https://kubernetes.github.io/ingress-nginx \
> --namespace ingress-nginx --create-namespace 



helm pull ingress-nginx/ingress-nginx --untar


```
