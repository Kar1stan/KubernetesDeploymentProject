# KubernetesDeploymentProject
***
Simple kubernetes deployment manifect creating deployment with 3 replicas/pods.

## 💻 Pre-requisites

Before you use this project you need to have Docker installed in your computer,and also Minikube.

https://www.docker.com/products/docker-desktop/
https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download

### Git clone
This will clone the project:
```
$ git clone https://github.com/Kar1stan/KubernetesDeploymentProject.git
$ cd KubernetesDeploymentProject
```

## 🚀 Run the manifest: 
To run the deployment,open the terminal and run:
```
$ kubectl apply -f deployment-myweb-v1.yaml
```
To delete deployment,open the terminal and run:
```
$ kubectl delete -f deployment-myweb-v1.yaml
```
To show details of the deployment,open the terminal and run:
```
$ kubectl describe deployment my-web-deployment
```
To connect IP and open server locally,open the terminal and run:
```
$ kubectl port-forward my-web-deployment 8888:80
```
