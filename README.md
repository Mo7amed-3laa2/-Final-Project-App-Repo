# Final Project App repo:

DevOps Challenge Demo which is aim to build a full GKE Private Cluster protected by IAP and deploying simple application to this cluster using load balancer service.

Note that the Commits related to the project building process.

## 1. Dockerize The Application.
Create the docker file that will dockerize the application from pipelines.

![image](https://user-images.githubusercontent.com/32172405/199647159-a6c768ce-ceee-45b4-82e8-f30a4bd0f1d6.png)

## 2. Create The Jenkins Pipeline Script.
Create the pipline script file that will pull the app-code from the repo then build the image, push it to the docker hub, and finally apply the deployments on our private GKE at app namespace

![image](https://user-images.githubusercontent.com/32172405/199646975-9e9cc648-9d35-43b7-b3c4-793a9a7bdfd4.png)


![image](https://user-images.githubusercontent.com/32172405/199647035-e83d2dfa-baca-4c8d-996b-05d0815303a4.png)

## 3. Create The Application Deployments files.

![image](https://user-images.githubusercontent.com/32172405/199647238-d51087d7-24b0-409d-9bf1-faa96cc1e2a8.png)

![image](https://user-images.githubusercontent.com/32172405/199647516-f4387a45-a5af-463a-94d4-2f8047b5bd68.png)

## 4. Test The Application.

![image](https://user-images.githubusercontent.com/32172405/199647621-b77083f9-1d61-4195-800a-d37f77d5db9d.png)

