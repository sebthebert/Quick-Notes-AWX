# Quick-Notes-AWX

Notes about AWX (upstream project for Tower)

## Installation on Docker

Clone the repository:

Get the latest Fedora image:
```
docker pull fedora:latest
```

docker run -v /Users/seb/Documents/github/awx/:/awx -it fedora bash

```
yum update
yum install ansible
yum install git
yum install npm
yum install nodejs-minimatch
yum install gcc
yum install gcc-c++
yum install findutils
yum groupinstall 'Development Tools'
```
