Ansible Role: Node
==================

## Example Playbooks

```yaml
- hosts: all
  become: yes
  roles:
    - role: node
      become_user: "{{ ansible_env.SUDO_USER }}"
      vars:
        node_home: "{{ ansible_env.PWD }}/.nvm"
```

