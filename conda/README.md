Ansible Role: Conda
===================

## Example Playbooks

```yaml
- hosts: all
  become: yes
  roles:
    - role: conda
      become_user: "{{ ansible_ssh_user }}"
```
