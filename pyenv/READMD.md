Ansible Role: pyenv
===================

## Example Playbooks

```yaml
- hosts: all
  become: yes
  roles:
    - role: pyenv
      become_user: "{{ ansible_ssh_user }}"
```

