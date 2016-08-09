ansible-role-googlechrome
=========================

Installs [Google Chrome](https://www.google.com/chrome).

Requirements
------------

A Linux distribution using either `apt` or `dnf`.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    channel: stable

Install Google Chrome from given channel.

Valid options:

- stable
- beta
- unstable

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      vars:
        - channel: beta
      roles:
         - { role: azmodude.googlechrome, become: yes }

License
-------

BSD

Author Information
------------------

None.
