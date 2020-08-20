# From Docker to Kubernetes: Set Up Instructions

## Prerequisites (Docker)

Before beginning this workshop, you must:

 - Install Docker ( [Instructions for Windows](https://docs.docker.com/v17.09/docker-for-windows/install/) / [Instructions for Macs](https://docs.docker.com/docker-for-mac/install/) )

 - Signup for an account in [Docker Hub](https://hub.docker.com/)

 - After signing up for an account, make sure you can login by running the following in your command line:

```
docker login
```

## Prerequisites (Kubernetes)

#### The Really Easy Way (Using Google Kubernetes Engine)

We can run the workshop with GKE (Google Kubernetes Engine), as part of Google Cloud. Google Cloud is one of the big three platform providers (along with AWS and Azure) that server a lot of the industry - and signup is simple. It's also *free*, as long as we clean up later.

Instructions are [in this link](/master/Setup-with-Google-Cloud.md). This is the best way to go!

Use this option if you are less familiar with the command line and want to experiment with Google Cloud.


#### The Not-so-easy Way (Using Minikube)

If you want to install a single-node Kubernetes cluster on your machine to play with, you can install with [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/). With this way, you'll be able to see your deployments with your browser. 

[If you are using a Windows computer, use the instructions here.](/Setup-with-Minikube-Windows.md)

[Otherwise, if you are using a Mac, use the instructions here.](/Setup-with-Minikube-Mac.md)

Use this option if you're more familiar with with the commandline. Keep in mind minikube is used for testing from your local machine and could be useful for your kubernetes usecase.

