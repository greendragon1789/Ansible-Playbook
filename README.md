# Ansible-Playbook
Script to run playbook

Command to checking Playbook:
```	$ ansible-playbook ansible_playbook/ssh_by_key.yml --ask-become-pass --check```

Command to run Playbook:
```	$ ansible-playbook ansible_playbook/ssh_by_key.yml --ask-become-pass```

Note: must be enter passwork have permission sudo, password of account in host file (same as sudo on linux).

If the system be configure sudo without passwork, command to run playbook for sudo without password:
```  $ ansible-playbook ansible_playbook/ssh_by_key.yml```
 
 In put variable when run command:
```  $ ansible-playbook ansible_playbook/create_user_keyauthen.yml -e "user_name='tiendinh'"```
