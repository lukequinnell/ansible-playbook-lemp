Ansible Playbook LEMP
=====================

Creates a Virtual Box with the following installed on it:
    - Ubuntu (latest stable release)
    - NGINX (latest stable release)
    - PHP5 (latest stable release)
    - MySQL (latest stable release)

Please ensure you have the latest version of Vagrant installed.

Installation
------------

1. `git clone git@github.com:lukequinnell/ansible-playbook-lemp.git`
2. Create `Vagrantfile` based off `Vagrantfile.dist` and change host and guest directories accordingly (line 32)
3. Create `vars/mysql.yml` based off `vars/mysql.yml.dist` and change connection details accordingly

Setup
-----

1. `vagrant init`
2. `vagrant up`
