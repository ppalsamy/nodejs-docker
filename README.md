# Nodejs Sample Application
Containerized nodejs hello world!
## Prerequisites
1. Node js 
2. Docker
## Configuration
1. package.json
2. Dockerfile
   - Base os is alphine with node js 
## Build
To Build docker image, run the below docker command, more options available [here]()

`docker build -t hello .` 

Image will be pushed to docker registry by default. Image can be pushed to own private registry. 
## Run
To Run Hello World application in docker

`docker run -p 8080:8080 hello`
