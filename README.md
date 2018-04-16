# Backend-env-ansible
Ansible deployment script for backend environment

### Installed packages
* brew
* pip
* gradle
* groovy
* docker
* nvm
* tree
* ...

### Usage
```
ansible-playbook -i "localhost," -c local env_setup.yml
```
### Parameters Description
``-i``: short for ``--inventory``. So by append ``"localhost,"``, it lead to the host of localhost

``-c``: short for ``--connection``. By appending ``local``, ansible will connect to localhost