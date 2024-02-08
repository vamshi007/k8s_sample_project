This is the sample project where in i've created a kubernetes yaml file.
1. front-end yaml pull the docker image from docker hub and which is sample react from end application
2. back-end yaml file pull the docker image from docker hub which has backend server which is developed using django framework

this yaml file create pod for back-end and front-end and based on the traffic the pods are scaled automatically.

front-end docker image : https://hub.docker.com/repository/docker/9440866803/frontend_0001/general
back-end docker image : https://hub.docker.com/repository/docker/9440866803/backend_0001/general

