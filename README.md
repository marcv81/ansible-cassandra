# Intro

This project helps to provision and maintain Cassandra clusters. It comes with a 3-nodes VirtualBox/Vagrant test environment.

## Security features

- Node-to-node encryption
- Client-to-node encryption
- Internal user authentication

# Setup

    vagrant up
    ansible-playbook -i environments/vagrant.py playbooks/site.yml
