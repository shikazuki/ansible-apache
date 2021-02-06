# ansible-apache

## Requirement
- Vagrant
- Ansible

## Preparation
```
$ vagrant up
$ vagrant ssh-config > ssh-config
```

## Run
```
$ ansible-playbook -i inventory.ini playbook.yml
```
