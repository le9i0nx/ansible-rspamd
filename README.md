[![Travis CI](http://img.shields.io/travis/le9i0nx/ansible-rspamd.svg?style=flat)](http://travis-ci.org/le9i0nx/ansible-rspamd) [![test-suite](http://img.shields.io/badge/test--suite-ansible--rspamd-blue.svg?style=flat)](https://github.com/le9i0nx/test-suite/tree/master/ansible-rspamd/) [![Ansible Galaxy](http://img.shields.io/badge/galaxy-le9i0nx.rspamd-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/5258)


### Installation

This role requires at least Ansible `v2.0.0.1-1`. To install it, run:

    ansible-galaxy install le9i0nx.rspamd

### Documentation

playbook
```
---

- name: rspamd install
  hosts: pve

  roles:

    - role: le9i0nx.rspamd
      tags: [ 'role::rspamd' ]
```

cat ./group_vars/pve.yml
```

```

### Role dependencies

### Authors and license

`rspamd` role was written by:
- Aleksej Gavrilov | [e-mail](mailto:le9i0nx@gmail.com) | [GitHub](https://github.com/le9i0nx)

License: [GPLv3](https://github.com/le9i0nx/ansible-rspamd/blob/master/LICENSE)

