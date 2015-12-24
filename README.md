# ansible-home

A collection of Ansible roles that I use on my home servers.

Not every one of these is truly generic. In other words, there may be a few things specific to my home setup that will need to be tweaked for you. Feel free to copy and learn from them though, or use them verbatim when possible.

## Important Notes

These roles are designed with Ubuntu in mind. They may or may not work on other Debian based systems.

You will need to drop your public SSH key into `roles/common/files/id_rsa.pub` or remove that task from the `common` role.

The `common` package that is included with every playbook installs SNMP. This may not be desirable for all. It also has my name and email in the SNMP configuration file. You'll probably want to change that.
