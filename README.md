install-asterisk
=========

This is the available role for installing Asterisk and it monitors the Asterisk 20 certified branch.

Requirements
------------

This role is for installing Asterisk from source on CentOS/Fedora. It will initially focus on the certified affiliate. CentOS is now required, versions 7 are supported.

Role Variables
-------------

(Not yet)

Installation via ansible-galaxy
--------------------------

Use ansible galaxy to download this role from:

ansible-galaxy install mbsutor.install-asterisk

Exemplary playbook
----------------

Here is an easy way to use it, after installing via ansible-galaxy, to install Asterisk:

 - hosts: servers
   roles:
     - { role: mbsutor.install-asterisk }


Use via git clone
-----------------

Alternatively, you can clone this repository and use the "test.yml" playbook example to test it and base your usage on that.

1. Clone the repository `git clone https://github.com/mbsutor/install-asterisk.git`
2. Change the specific hosts in the `test.inventory` file.
3. Run: `ansible-playbook -i test.inventory test.yml`

License
-------

MIT

Author information
------------------

Mikhail Sutorikhin
@mbsutor
