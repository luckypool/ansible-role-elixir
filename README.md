luckypool.elixir
================

[![Build Status](https://travis-ci.org/luckypool/ansible-role-elixir.svg?branch=master)](https://travis-ci.org/luckypool/ansible-role-elixir)

Install [elixir](http://elixir-lang.org/install.html#unix-and-unix-like) to ubuntu.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Tested env:

```
  min_ansible_version: 2.1.0
  platforms:
    - name: Ubuntu
      versions:
        - trusty
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: luckypool.elixir }

License
-------

MIT

Author Information
------------------

Bug reports and pull requests are welcome on GitHub at [https://github.com/luckypool/ansible-role-elixir](https://github.com/luckypool/ansible-role-elixir)
