Core
========

Install llama dotfiles (https://github.com/llamadigital/dotfiles.git), installs IDE packages (used in dotfiles) and sets locale to GB

Requirements
------------

Ideally llama dotfiles cloned and installed on host machine

Role Variables
--------------

distro: ubuntu
locale: en_GB.UTF-8
timezone: Europe/London
skip_locale: default
skip_ide: default

Dependencies
------------

None

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: default
      vars:
        - distro: debian
      roles:
        - shadowkobolt.core

License
-------

BSD

