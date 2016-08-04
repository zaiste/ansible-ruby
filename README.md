ansible-ruby
=========

An Ansible role that installs Ruby on Ubuntu Xenial from source or through PPA.

Requirements
------------

None.

Role Variables
--------------

* `ruby_version` defaults to `2.3`
* `from_source` defaults to `false`

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

[Zaiste](http://zaiste.net) 2014 - 2016
