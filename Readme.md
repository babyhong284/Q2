
![Screenshot 2024-09-23 211045](https://github.com/user-attachments/assets/6e98481f-7947-4572-abf5-45662a6d46f5)

Buy SSL from provider or Let's Encrypt to create free SSL.
after SSL Cert and key generated, then create secret. 
Create SSL before apply ingress_with_ssl.yaml

kubectl create secret tls example-tls --cert=tls.crt --key=tls.key


kubectl apply -f Q2/

kubectl get deployment
kubectl get hpa
kubectl get ing
kubectl get svc
kubectl get cm
kubectl get secret
kubectl get pv
