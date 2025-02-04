# ArgoCD Example Apps

This repository contains example applications for  ArgoCD functionality.we use guestbook sample example to test and run argocd. following steps below to launch application in minikube
cluster. 

create new namespace and install argocd 

1.kubectl create namespace argocd

2.kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml


3) check services in argocd namespace

    ![image](https://github.com/user-attachments/assets/aa67f4cf-9b54-4586-9480-67d98a73a49d)


4)
