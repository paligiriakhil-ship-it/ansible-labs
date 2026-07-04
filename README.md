# Ansible Labs

## Topics

- Inventory
- Playbooks
- Variables
- Roles
- Templates

---

## Sample Playbook

```yaml
---
- hosts: all

  become: yes

  tasks:

  - name: Install nginx

    apt:

      name: nginx

      state: present
```
