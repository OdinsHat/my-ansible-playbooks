Ansible Playbooks
=================

Although [Ansible Galaxy](https://galaxy.ansible.com/) is now considered the right way of managing your 
Ansible config and setup I still use the following files for quick setup and upgrade of the servers I 
manage to get them to a basic level.

* Some basic packages including php, vim, nginx, zsh, python, pip, etc.
* Setting up of Python: pip, Python MySQL, uwsgi, virtualenvwrapper, etc.
* Setting up of MySQL.
* Settign up of basic Git config.
* Setting up of [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh)

Then an upgrade playbook for upgrading the packages installed as well as the apt cache.

These plkaybooks have been used and are compatible on Ubuntu 12.04 and Debian 6.0 (Squeeze)
