# personal-ansible
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://github.com/AleksaC/personal-ansible/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/AleksaC/personal-ansible.svg?branch=master)](https://travis-ci.org/AleksaC/personal-ansible)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/AleksaC/rsa/blob/master/.pre-commit-config.yaml)

Ansible playbooks for configuring my development environment.

## About

This repository contains ansible playbook for installing most of the programs I
use on my personal machine. I use Ubuntu 20.04, but most of the roles here should
work on other versions with little to no modification. To see which programs are
installed look inside the roles directory as most of the programs are installed
in a separate role and the ones that are not are either indispensible
(like git, curl etc.) or mostly insignificant.

## Usage
You can install everythin with a singel command on a clean isntall:
```shell script
wget -O - "https://raw.githubusercontent.com/AleksaC/personal-ansible/master/run.sh" | bash
```
To only run the playbook use:
```shell script
ansible-playbook main.yml -K
```

## Contact
- [Personal website](https://aleksac.me)
- <a target="_blank" href="http://twitter.com/aleksa_c_"><img alt='Twitter followers' src="https://img.shields.io/twitter/follow/aleksa_c_.svg?style=social"></a>
- aleksacukovic1@gmail.com
