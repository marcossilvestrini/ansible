# Leaning Ansible

![Ansible](https://user-images.githubusercontent.com/62715900/118187521-6a8efa00-b415-11eb-9479-6d73e36886a3.png)

## Getting Started

Fork the project and enjoy.\
Atention for pre requisites and License!!!

## Prerequisites

Virtual Box\
Vagrant\
Ansible\
Python3

## Authors

Marcos Silvestrini

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## References

[Virtualbox Docs](https://www.virtualbox.org/wiki/Documentation)\
[Vagrant Docs](https://www.vagrantup.com/docs/index.html)\
[Ansible Main Page](https://docs.ansible.com/)\
[Ansible Core Docs](https://docs.ansible.com/ansible-core/devel/index.html)

## Install Ansible in Rhel Centos 7\8

`sudo yum install epel-release`
`sudo yum install ansible`

## Ad-Hoc Commands

### Collect and Display infos of server

`ansible localhost -m setup`

### Check all  my inventory  hosts are ok

`ansible all -m ping`

### Check uptime

`ansible protheus -m command -a "uptime"`

## Check playbook syntax

`ansible-playbook playbook.yml --syntax-check`

## Roles

### Wordpress

Up Wordpress Stack with vagrant and ansible

### Protheus

Up Protheus Stack with vagrant and ansible
