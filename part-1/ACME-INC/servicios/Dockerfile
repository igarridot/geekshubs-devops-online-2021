FROM jenkins/jenkins:lts-slim

USER root
RUN apt-get update && apt-get install -y -q docker.io && rm -rf /var/lib/apt/lists/*
USER jenkins
