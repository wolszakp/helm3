# Script to go through this excercise 


```bash
helm list
helm install demo-guestbook guestbook
k get pods
curl frontentd.minikube.local
minikube ip
sudo nano /etc/hosts
cat /etc/hosts
helm list
curl frontend.minikube.local
helm lint guestbook
# Upgrad frontend.yaml image to 1.1 and appVersion in Chart to 1.1
helm upgrade demo-guestbook guestbook
helm rollback demo-guestbook 1
helm history demo-guestbook 
helm list
helm uninstall demo-guestbook 
helm list
```