# tutorial-jenkins-pipeline
https://medium.com/@sontung0/basic-ci-cd-with-jenkins-a43ef8b77039


Bỏ `rm` để khỏi xóa container jenkins khi stop
```
docker run -u root -d -p 8080:8080 -p 50000:50000 -v jenkins-data:/var/>jenkins_home -v /var/run/docker.sock:/var/run/docker.sock jenkinsci/blueocean
```
