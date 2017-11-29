ansible-ruby
=========

An Ansible role that installs Ruby on Ubuntu from source.

Requirements
------------

None.

Role Variables
--------------

* `ruby_version` defaults to `2.4`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: zaiste.ruby }

Roadmap
-------

- [ ] move `ruby_source_url` to `vars` as it should not be overridden

License
-------

MIT / BSD

Author Information
------------------

[Zaiste](http://zaiste.net) 2017 
