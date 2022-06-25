# flask-k8-docker


```
docker build -f Dockerfile -t hello-python:latest .
```


```
docker image ls
docker run -dp 5000:5000 hello-python
```


```
kubectl apply -f deployment.yaml
kubectl get deployments
kubectl get pods
kubectl get services
```


```
docker login
docker tag hello-python <your-docker-hub-username>/hello-python
docker push <your-docker-hub-username>/hello-python
