This playbook installs Jenkins on CentOS7.

# Install Jenkins

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml -e '@vars/default.yml'
```

# Ansilbe Vars
See 'vars/default.yml'

