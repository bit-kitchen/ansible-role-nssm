ansible-role-nssm
=================

[![Ansible Role: bit_kitchen.nssm](https://img.shields.io/ansible/role/46872.svg)](https://galaxy.ansible.com/bit_kitchen/nssm)
[![Build Status](https://travis-ci.org/bit-kitchen/ansible-role-nssm.svg?branch=master)](https://travis-ci.org/bit-kitchen/ansible-role-nssm)

Install [nssm](https://nssm.cc/), satisfying requirements of [win_nssm](https://docs.ansible.com/ansible/latest/modules/win_nssm_module.html).

This role will do nothing on Linux, so that it can be depended on by roles compatible with both Linux and Windows.

    ansible-galaxy install bit_kitchen.nssm

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: win_servers
      roles:
        - bit_kitchen.nssm

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
