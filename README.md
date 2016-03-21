# Ansible Planet

an Ansible role of a site based on Python, Nginx, Supervisor, Redis and Postgresql.

## playbook.yml

```
---
- hosts: all
  sudo: true

  roles:
    - Stouts.python
    - Stouts.nginx
    - Stouts.supervisor
    - Stouts.redis
    - Stouts.postgresql
```