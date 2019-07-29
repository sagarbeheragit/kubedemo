# kubedemo
This is simple example explaining the kubernetes demo
# Docker File 
The docker file uses the server.js file to implement a simple node application. You can build the image based on the dockerfile using thr docker build command.

# Deployment.yml

This file is the input to the kubernetes cluster. Its a simple deployment file having just one replica, image and port exposing. 
You can use the kubectl apply commmand to deploy this deployment and then run kubectl expose command to expose this as a service.
