# Git + Kustomize

[![DockerHub Git Kustomize](https://img.shields.io/badge/DockerHub-buildscale%2Fgit--kustomize-blue)](https://hub.docker.com/repository/docker/buildscale/git-kustomize)

Minimal Git + Kustomize docker image for use in GitOps workflows where `kustomization.yaml` is updated with the docker image version/hashref as part of the CI/CD workflow (eg. to then be deployed via ArgoCD or similar from Git).

OpenSSH Client is included because it is necessary for Jenkins ssh-agent functionality to execute inside the container for Git repo access via ssh.

### Jenkins usage example

  https://github.com/BuildScale/Templates/blob/master/vars/gitOpsK8sUpdate.groovy

  https://github.com/BuildScale/Kubernetes-configs/blob/master/jenkins-agent-pod.yaml

  https://github.com/BuildScale/Templates/blob/master/Jenkinsfile

### Kubernetes kustomization examples

  https://github.com/BuildScale/Kubernetes-configs


Related Docker images can be found for many Open Source, Big Data and NoSQL technologies on [my DockerHub profile](https://hub.docker.com/r/buildscale). The source for them all can be found in the [master Dockerfiles GitHub repo](https://github.com/BuildScale/Dockerfiles/).