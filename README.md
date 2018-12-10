## docker_android_build

## Android build with jenkins and Docker
Build Android Project with Jenkins and Docker

### run below command to build your own Jenkins with Android library
docker build -t myjenkins/blueocean .

### Run your docker with jenkins
docker run  -u root   --rm  -d   -p 8080:8080   -v jenkins-data:/var/jenkins_home   -v /var/run/docker.sock:/var/run/docker.sock myjenkins/blueocean


### Blueocean Jenkins
https://jenkins.io/doc/book/blueocean/getting-started/
