bootstrap
=========

Sets up a new system with some basics.

* hostname
* hosts
* vimrc.local
* ansbile min required packages

Requirements
------------

* Ubuntu (Debian)

Role Variables
--------------

bootstrap_hostname: myhostname
bootstrap_domain: localdomain.com

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - role: gotansible.bootstrap
		 bootstrap_hostname: web-01
		 bootstrap_domain: myorg.prod
```

License
-------

MIT

Author Information
------------------

Created by Franklin Wise in Santa Monica, CA.
