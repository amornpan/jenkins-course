jenkins-course
docker run -p 8080:8080 -p 50000:50000 -v /var/jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock --name jenkins -d jenkins-docker

docker pull amornpan/docker-node-js-demo:latest

docker run -p 3000:3000 -d --name my-nodejs-app amornpan/docker-node-js-demo:latest
