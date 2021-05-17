# Provision VM for Developer with nginx

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

[Virtual Box Docs](https://www.virtualbox.org/wiki/Documentation)
[Vagrant DoCS](https://www.vagrantup.com/docs/index.html)
[Ansible Docs](https://docs.ansible.com/)
[Nginx Docs](https://nginx.org/en/docs/)

## Install Vagrant in Rhel Centos 7\8

### Download

https://releases.hashicorp.com/vagrant/2.2.7/vagrant_2.2.7_x86_64.rpm\
sudo wget https://releases.hashicorp.com/vagrant/2.2.7/vagrant_2.2.7_x86_64.rpm

### Install

sudo yum localinstall vagrant_2.2.7_x86_64.rpm -y\
vagrant ––version

## Project Structure

### Provisioning

Ansible structure with inventory, playbooks and roles. This structure is responsible for provisioning the infraestructure of project

### Security

Important!!!\
This structure is path for generate your ssh key pair.

## Vagrantfile

Configure Network\
Configure Mounts\
Configure ssh\
Configure Firewall (firewalld or iptables)\
Configure Selinux\
Install Updates\
Install Python3

## Provisioning (Ansible)

### Role Nginx

foo\
bar
