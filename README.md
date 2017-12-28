# Ansible fetch roles
###### Ansible playbook to fetch all roles from file locally with `.git` :+1:

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)

## Requirements
```
	Ansible : <1.9 min
	Ope. System : Mac OS, Linux ...
```

## Variables

Example source file :
```yaml
    repo_roles:
      - src: git@github.com:slgevens/ansible-ssmtp.git
        name: sSMTP
        version: master
      - src: git@github.com:slgevens/syslog-ng.git
        name: syslog-ng
        version: master
      - src: git@github.com:slgevens/ansible-rsyslog.git
        name: rsyslog
        version: master
```
## Author
Evens SOLIGNAC