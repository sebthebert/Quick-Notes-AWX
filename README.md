# Quick-Notes-AWX

Notes about AWX (upstream project for Tower)

![First Login](/AWX_first_login.png)

## Build AWX on Docker

### Centos

Clone the repository:

Get the latest Centos image:
```
docker pull centos:latest

docker run -v /Users/seb/Documents/github/awx/:/awx -it centos bash
```

```
yum install epel-release -y
yum update -y && yum install ansible -y

ansible-playbook -i inventory install.yml
```

### Fedora

Get the latest Fedora image:
```
docker pull fedora:latest

docker run -v /Users/seb/Documents/github/awx/:/awx -it fedora bash
```



```
yum update -y && yum install ansible -y

ansible-playbook -i inventory install.yml
```
