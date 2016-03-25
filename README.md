hearstat/jenkins-jlnp-slave
================

Container to be utilized with the Jenkins Docker Plugin (experimmental) or with AWS ECS plugin

## Latest Build Info
* Base Image: ubuntu:xenial
* openJDK: 8
* Remoting: 2.56

## Trusty Build Info
* Base Image: ubuntu:trusty
* openJDK: 7
* Remoting: 2.56

## Usage

```
FROM jenkins-jnlp-slave:xenial
```

## Building

To build the image, do the following:

```
% docker build github.com/hearstat/docker-jenkinsjnlp
```

A prebuilt container is available in the docker index.

```
% docker pull hearstat/jenkins-jlnp-slave
```
