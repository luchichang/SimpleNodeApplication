#  TODO Node App

## Description;
       A simple node js Application which runs the todo app 

### Steps to run this app locally 

* install the Application Dependencies 
     
           npm install
   
  or
  
         yarn install --production

* Run the Application Locally
     
        node ./src/index.js

__Application can be accessed in your <Public/Private IP>:3000__

<br>
hurray 🥳 App Launched Successfully

<a>![image](https://github.com/user-attachments/assets/3bffab0a-51c6-465a-9691-47db2fb6b4da)</a>
---
## Steps for Running the application in a Containerised way 
* set your current working directory inside the app, this can be done by using the **cd** Command
* Build the Docker image from the docker file or directly pull the image from container Registry

       docker build -t node-app-image  .
  or <br>
  
         docker pull dinesht0006/basic-todo-nodejs-app:latest
* now run the container <br>

         docker run --name <ContainerName> -p 3000:3000 -itd node-app-image  

now application is running without installing or manually setting up the environment. yes that's the docker way 😉🆒!!
