# Kubernetes
Deployed a Kubernetes cluster using Minikube for a Node JS application which uses a mongoDB backend.
The application deployed on K8s uses Node JS image from docker hub for the front end and Mongo DB image for the backend

## This application is built and tested in my local system using minikube
I have used various kubernetes componenets in this process for example secret , ConfigMap, Deployement, Service

    Secret : used to store credential
    ConfigMap : storing endpointURL
    Deployement : contains all the information about the pods and container
    Services : provide a stable endpoint for pods and also provide internet connectivity in our cluster(External Service) 


## Kubernetes Cluster Deployed
 <img src="https://user-images.githubusercontent.com/126198458/228353050-b1256da3-77b1-413d-a450-61a5a69755b1.png"  width="650" height="350">
 
