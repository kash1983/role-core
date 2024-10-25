# Ansible Role: core

Diese Rolle bringt globale Helper mit. Bspw. für die Versionierung, das Role-Forcing, etc. .

> **HINWEIS:** Diese Rolle im Playbook via `include_role` mit `tasks_from` Attribute nutzen.


## Mögliche Optionen

kein direkter Aufruf und keine direkter Aufruf via Tags.

## Include Möglichkeiten

### Role Forcing
Tag `force-roles`:
```
- include_role: name=bzm_role-core tasks_from=force-roles
  tags: always
```
