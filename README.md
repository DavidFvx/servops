# servops

## Introduction

This project deploy a basic server application.

The main purpose of the project is to put into practice a use case of devops technologies.

Technologies used :
- Docker
- Nginx
- Ansible

I'm deploying in local with a raspberrypi.

## Interactions

- Ansible : deploy the application.
- Docker : containerise nginx, the application and the database application.
- Nginx : allows to connect docker containers together and to the network

## Stages

- [ ] Ansible
  - [x] Ansible / raspberrypi server connection
  - [x] Install docker
  - [ ] Run docker-compose
- [ ] Docker
  - [ ] Nginx container / application container connection
  - [ ] Database container image : store a picture with persistence
  - [ ] Application container image : show a picture
  - [ ] Application container / database containers connection
  - [x] Run a nginx container
