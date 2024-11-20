run jenkins from container:

docker run -p 8080:8080 -p 50000:50000 -d --restart=on-failure -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts

Jenkins password secret:

/var/jenkins_home/secrets/initialAdminPassword