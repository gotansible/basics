Basics
=========

[![Build Status](https://travis-ci.org/gotansible/basics.svg)](https://travis-ci.org/gotansible/basics)

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

basics_hostname: myhostname
basics_domain: localdomain.com

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - role: gotansible.basics
		 basics_hostname: web-01
		 basics_domain: myorg.prod
```

License
-------

MIT

Author Information
------------------

Created by Franklin Wise in Santa Monica, CA.
