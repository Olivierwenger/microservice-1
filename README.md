# microservice-1
Tutorial Udemy with self-implemented event-bus

# requirements
Kubectl with a runnig kubernetes cluster (I used minikube)
npm
skaffold for continuis development

# Run it
at the root run
```
skaffold dev
```

check the cluster ip address with
```
minikube ip
```

add the following dns records in /etc/hosts (with thi ip from cluster)
```
172.17.0.2 posts.com
```
