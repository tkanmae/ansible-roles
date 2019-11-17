Ansible Role: Conda
===================

## Example Playbooks

```yaml
- hosts: all
  become: yes
  roles:
    - role: conda
      become_user: "{{ ansible_env.SUDO_USER }}"
      vars:
        conda_home: "{{ ansible_env.PWD }}/.miniconda3"
```
