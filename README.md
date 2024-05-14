# infra-nginx-ingress-trial

```bash

helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx



helm repo update



helm upgrade --install ingress-nginx ingress-nginx \
--repo https://kubernetes.github.io/ingress-nginx \
--namespace ingress-nginx --create-namespace




helm pull ingress-nginx/ingress-nginx --untar


```


Images of the Application Deployed (For Reference)

<img width="1512" alt="Screenshot 2024-05-14 at 4 36 35 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/d071bce1-0eae-4622-95a5-ced3416fe6b1">

<img width="1512" alt="Screenshot 2024-05-14 at 4 37 46 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/9f5dc358-c19a-4d46-9ad6-707598250fa1">

<img width="1512" alt="Screenshot 2024-05-14 at 4 39 57 PM" src="https://github.com/RohanRusta21/infra-nginx-ingress-trial/assets/110477025/eb6f8676-7b0b-47b6-8962-cb68138c383f">











