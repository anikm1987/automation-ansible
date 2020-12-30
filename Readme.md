Automation using Ansible
--------

Getting Started
---------------
- Installing and configuring ansible for control machine
    - ./install_ansible.sh
    - ./configure_docker_local.sh


- Every installation in local machine should be also managed using playbook


Features
----------
- Install ansible
- Configure local machine / control machine with required apt packages 
- Docker & docker-compose install
- operations folder contains roles to configure local machine 


TODO:
----------
- Make sure docker installation is fine, it should not delete at the start , should be based on some flag may be
- Add steps to yaml file to verify that the docker is installed.

