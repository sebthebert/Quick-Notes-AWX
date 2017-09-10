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
yum install gcc
yum install gcc-c++
yum install findutils
yum groupinstall 'Development Tools'

# Fix 'bzip2: Cannot exec: No such file or directory' when installaing phantomjs
yum install bzip2 -y 

npm i -g npm@3.10.10
npm i -g minimatch@3.0.2

pip install docker-py


ansible-playbook -i inventory install.yml
```
