Kubernetes Lab for Engineering
------------
Learning how to interact with, and use kubernetes in your daily workflow

# Required Tools

## Git

## SSH

## Kubectl

[https://kubernetes.io/docs/reference/kubectl/overview/](https://kubernetes.io/docs/reference/kubectl/overview/)

`kubectl` is a command line interface for running commands against Kubernetes clusters.

### Install

`brew install kubectl`

## Telepresence

[https://www.telepresence.io/discussion/overview](https://www.telepresence.io/discussion/overview)

`telepresence` is an open source tool that lets you run a single service locally, while connecting that service to a remote Kubernetes cluster.

### Install

```
brew cask install osxfusectl
brew install socat datawire/blackbird/telepresence
```

# Getting Access

  

# Cheat Sheet

How to read some of the commands

## Logging

### W/ just kubectl

`kubectl logs -f --tail=10 <pod_name> [<container_name>]`

This will follow the live logs of a container in a pod. The --tail=10 will also show the last 10 lines of the log before following.

### Kail

### Kubetail


> Written with [StackEdit](https://stackedit.io/).
