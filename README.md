
# Ansible Integration into Jenkins



## Description

A DevOps project made by **Jenkins CI/CD, Ansible, Docker, Shell Script, AWS and CIVO Cloud.**

Ansible is used automate the process of making servers ready for deployment and then deploy the application on it by writing ansible playbooks which makes the deployment process efficient and to deploy the application with same configuration on any number of servers in few seconds.

- A jenkins server is setup on CIVO Cloud.
- Ansible server is also setup on CIVO Cloud.
- Copy deploy files from GitHub to ansible server with Jenkinsfile.
- Ansible server is setup with the shell script file with docker install.
- After copying all the neccessary files, ran the ansible playbook to deploy application on AWS Cloud with the help of docker.



## Project Flow Chart

![ss1](https://github.com/AkramExp/jenkins-ansible/blob/main/screenshots/ss1.png)
