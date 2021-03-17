# AWS Lightsail

## Lightsail

### Blueprints

    aws lightsail get-blueprints| grep group

## Start Container

    docker-compose run --rm ansibleaws  bash

    ansible-galaxy collection install community.aws

## Ansible Playbook

    ansible-playbook -i inventory/ansible_hosts.yml lightsail-instances.yml
