# Ansible role for installing ionCube Loader on a LAMP stack

![screenshot](https://raw.github.com/vivaserver/ansible-ioncube/master/screenshot.png)

This Ansible Galaxy role installs the [ionCube Loader][ion] on a LAMP stack. This loader is required to run some encoded PHP applications such as [WHMCS][whmcs].

Since the loader version depends on the specific PHP version installed, this role has as a dependency the [vivaserver.lamp][lamp] role for installing ionCube 4.5.3 on the PHP 5.3 package of Ubuntu 12.04. Other PHP versions might require a different loader version, so they're not supported by this role.

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
