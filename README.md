# Infrastructure
Ansible Playbook for deploying and configuring and hardening Apache Tomcat

[![Generic badge](https://img.shields.io/badge/Ansible-Tomcat-<COLOR>.svg)](https://shields.io/)
![star this repo](http://githubbadges.com/star.svg?user=arisath&repo=Infrastructure)

### Hardening includes
```
Running tomcat with dedicated user and group
Removing default web applications
Removing examples
Making conf folder readable only from the user running tomcat
Running tomcat as a service on start-up
```

### Prerequisites
```
Python 2.7
Ansible ......
```

### Installing
```
ansible-playbook playbook.yaml
```




