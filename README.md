# Ansible Sudoers Module

This is a basic Ansible module to facilitate adding Sudoers config to the /etc/sudoers.d/ directory.

This module does not currently attempt to support all options supported by Sudoers.
The case this module currently handles is when a Sudoers rule to grant a single or list of commands (or `ALL`) sudo access with or without a password requirement.

It supports granting by user or by group.
It does not currently support aliases, but it is probably not too difficult to add.
