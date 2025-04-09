# GoLang Time App

A simple Go web app that displays current date & time.

## Docker
```
docker build -t yourdockerhub/time-app .
docker push yourdockerhub/time-app
```

## Kubernetes
```
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

App will be available on `NodeIP:30036`.