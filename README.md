[![](https://github.com/ansible-playbooks-centos7/jenkins_install/workflows/build/badge.svg)](https://github.com/ansible-playbooks-centos7/jenkins_install/actions?query=workflow%3Abuild)

This playbook installs Jenkins on CentOS7.

# Install Jenkins

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml -e '@vars/default.yml'
```

# Ansible Vars

### Boostrap
[robertdebock/ansible-role-bootstrap: Prepare your system to be managed by Ansible. - GitHub](https://github.com/robertdebock/ansible-role-bootstrap)

### Docker
[geerlingguy/ansible-role-docker - GitHub](https://github.com/geerlingguy/ansible-role-docker)

### Epel
[robertdebock/ansible-role-epel: Install epel on your system. - GitHub](https://github.com/robertdebock/ansible-role-epel)

### Git
[geerlingguy/ansible-role-git - GitHub](https://github.com/geerlingguy/ansible-role-git)

### Locale
[robertdebock/ansible-role-locale: Configure locale on your system. - GitHub](https://github.com/robertdebock/ansible-role-locale)

### Java
[geerlingguy/ansible-role-java - GitHub](https://github.com/geerlingguy/ansible-role-java)

### Jenkins
[geerlingguy/ansible-role-jenkins - GitHub](https://github.com/geerlingguy/ansible-role-jenkins)

### Pip
[geerlingguy/ansible-role-pip - GitHub](https://github.com/geerlingguy/ansible-role-pip)
