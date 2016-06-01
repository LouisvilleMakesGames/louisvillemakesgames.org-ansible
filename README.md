# louisvillemakesgames.org-ansible
[Ansible](http://docs.ansible.com/index.html) playbooks for setting up [LouisvilleMakesGames.org](http://louisvilleMakesGames.org) servers.

Initial server setup:
```
ansible-playbook -i ansible_hosts production.yml
```

Deploy site:
```
ansible-playbook -i ansible_hosts deploy.yml
```
