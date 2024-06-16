Role Name
=========

An Ansible Role that installs the OpenShift client tool `oc` on Linux.

Requirements
------------

None.

Role Variables
--------------

| Variable | Default Value | Description |
|----------|---------------|-------------|
| `oc_client_install_path` | `/usr/local/bin` | Installation path for binary. |
| `oc_client_version` | `latest` | OpenShift client version. |
| `oc_client_download_url` | `https://mirror.openshift.com/pub/openshift-v4/clients/ocp` | Download URL for the client. |

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - Skalador.oc_client
```

License
-------

Apache-2.0

Author Information
------------------

This role was created by [Kevin Niederwanger](https://github.com/Skalador).
