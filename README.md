# ansible-playbooks
Collection of Ansible playbooks I use

## Hosts file
```
[all:vars]
ansible_user='<username>'
ansible_become=yes
ansible_become_method=sudo
ansible_python_interpreter='/usr/bin/env python3'

[ubuntu_servers]
<list of debian/ubuntu servers>

[suse_servers]
<list of opensuse servers>
```
