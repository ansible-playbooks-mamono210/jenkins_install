This playbook installs Jenkins on CentOS7.

# Install Jenkins

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


