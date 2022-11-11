FROM jenkins/jenkins:lts

RUN apt-get update
RUN chmod a+r /etc/apt/keyrings/docker.gpg
RUN apt-get update
RUN apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin