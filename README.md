# kubectl-bash

Simple Docker image with kubectl and bash for CI/CD

[![Dockerhub](https://img.shields.io/badge/image%20size-21.9MB-blue.svg)](https://hub.docker.com/r/maslick/kubectl-bash)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Features
* kubectl v1.16.3 (latest)
* bash v5.0
* tls root certificates

## Usage
```zsh
docker run -ti maslick/kubectl-bash bash
bash-5.0# kubectl version
Client Version: version.Info{Major:"1", Minor:"16", GitVersion:"v1.16.3", GitCommit:"b3cbbae08ec52a7fc73d334838e18d17e8512749", GitTreeState:"clean", BuildDate:"2019-11-13T11:23:11Z", GoVersion:"go1.12.12", Compiler:"gc", Platform:"linux/amd64"}
```

## Build
```zsh
docker build -t maslick/kubectl-bash .
```
