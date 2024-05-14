# infra-nginx-ingress-trial Task

Your task entails the implementation of a custom helm chart that deploys your own nginx-ingress with custom variables.

You must deploy a custom chart for nginx-ingress using the latest version and name it infra-nginx-ingress-trial. Since this deployment will be composed of custom variables, download the chart and exchange the values to the requirements.
Requirements *

1. The nginx-ingress will be able to expose ingresses

2. The nginx-ingress will only search for specific ingresses with annotation nginx-trial, not all existent ingresses


## Commands used throuhout deployment

```bash

helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx

helm repo update

helm upgrade --install ingress-nginx ingress-nginx \
--repo https://kubernetes.github.io/ingress-nginx \
--namespace ingress-nginx --create-namespace

helm create infra-nginx-ingress-trial

```

## NOTE : Used a custom domain and resolve its dns with the hostmachine. Modified /etc/hosts file which includes the ip address and domain used in the task.


Images of the Application Deployed (For Reference)

<img width="1512" alt="Screenshot 2024-05-14 at 4 36 35 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/d071bce1-0eae-4622-95a5-ced3416fe6b1">

<img width="1512" alt="Screenshot 2024-05-14 at 4 37 46 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/9f5dc358-c19a-4d46-9ad6-707598250fa1">

<img width="1512" alt="Screenshot 2024-05-14 at 4 39 57 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/eb6f8676-7b0b-47b6-8962-cb68138c383f">

<img width="1512" alt="Screenshot 2024-05-14 at 4 51 49 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/ce62b851-b715-4e7d-873d-8bed17df4762">











