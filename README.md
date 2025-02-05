# ArgoCD Example Apps

This repository contains example applications for  ArgoCD functionality.we use guestbook sample example to test and run argocd. following steps below to launch application in minikube
cluster. 

create new namespace and install argocd 

1.kubectl create namespace argocd

2.kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml


3. check services in argocd namespace

    ![image](https://github.com/user-attachments/assets/aa67f4cf-9b54-4586-9480-67d98a73a49d)


4. create app in argocd web ui


   ![image](https://github.com/user-attachments/assets/9fb19ac9-f62e-4df6-95e2-e61b6e0ed8f0)





6. edit argocd port type as NodePort instead of cluster type 

  ![image](https://github.com/user-attachments/assets/88c18ccb-19de-4beb-b7f2-f7b9dda36ab7)


  ![image](https://github.com/user-attachments/assets/7ecdf84e-2fa5-4c02-a4a7-7becb5786714)



5. view the secrets file and view encrypted password for login

![image](https://github.com/user-attachments/assets/d500c1c4-3dea-42a9-83b2-80d713272f6f)


6. decode value using base64 decode flow to get actual password


7. open nodeport url to open app.

   http://192.168.59.100:31578


   ![image](https://github.com/user-attachments/assets/be70d0b0-961b-48c0-a66c-aa107ad0edaf)


   




