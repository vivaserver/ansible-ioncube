# Ansible role for installing ionCube Loader on a LAMP stack

This Ansible Galaxy role installs the [ionCube Loader][ion] on a LAMP stack. This loader is required to run some encoded PHP applications such as [WHMCS][whmcs].

Since the ionCube Loader version depends on the specific PHP version installed, this role has as a dependency the [vivaserver.lamp][lamp] role.

## Requirements

Ubuntu 12.04, including [elementaryOS][eos] 0.2 "Luna".

## Dependencies

Ansible Galaxy [vivaserver.lamp][lamp] role.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vivaserver.ioncube

## License

MIT

## Copyright

(c)2014 Cristian R. Arroyo

[ion]: http://www.ioncube.com/loaders.php
[lamp]: https://github.com/vivaserver/ansible-lamp
[whmcs]: http://www.whmcs.com/ 
[eos]: http://elementaryos.org
