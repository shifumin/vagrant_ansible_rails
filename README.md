Vagrant-Ansible-Rails
===============
This is Ansible playbook to provision a Rails box suitable for production on a local Vagrant environment.

## Stack
* Git
* (dotfiles)
* Zsh
* Oh-My-Zsh
* rbenv

## Environment
* Ansible 1.9.2
* Vagrant 1.7.2
* Virual Box 4.3.30

## Usage(CentOS6.6)

```
$ git clone git@github.com:shifumin/vagrant-ansible-rails.git
$ cd vagrant-ansible-rails
$ vagrant init chef/centos-6.6
$ vagrant up
```
