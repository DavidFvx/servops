# servops

## Introduction

This project deploy a basic server application.

The main purpose of the project is to put into practice a use case of devops technologies.

Technologies used :
- docker
- nginx
- ansible
- terraform

I'm deploying in local with a raspberrypi.

## Interactions

- Ansible : deploy the application.
- Docker : containerise nginx, the application and the database application.
- Nginx : allows to connect docker containers together and to the network
- Terraform : TODO

## Stages

- [ ] Ansible
  - [ ] Ansible / raspberrypi server connection
  - [ ] Install docker
  - [ ] Run docker-compose
- [ ] Docker
  - [ ] Application image
  - [ ] Database image
  - [ ] Run a nginx container
  - [ ] Nginx connection with local network
  - [ ] Setup containers network
- [ ] Terraform
  - [ ] TODO
