# Ansible Vagrant LAMP
Configuration to use Vagrant and Ansible to build LAMP development environment

The Machine box based on ubuntu/precise64 http://files.vagrantup.com/precise64.box

### The packages are
1. Apache2
2. PHP 5.5
3. MySQL
4. Vim

### Prerequisite 
1. Install [vagrant](http://www.vagrantup.com/downloads.html)
2. Install [virtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html)
3. Install [ansible](http://docs.ansible.com/intro_installation.html#installing-the-control-machine)

### Instalation
1. Clone `git clone https://github.com/iwanwan/ansible-vagrant-lamp.git`
2. `cd ansible-vagrant-lamp` 
3. `vagrant up`
4. Test it, open the browser `http://localhost:8080/info.php`
