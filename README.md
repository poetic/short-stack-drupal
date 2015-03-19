Short Stack: Drupal
=========
[![Build Status](https://travis-ci.org/poetic/short-stack-drupal.svg)](https://travis-ci.org/poetic/short-stack-drupal)

Installs drush.

Requirements
------------

This role is meant to be used with [Short Stack](https://github.com/poetic/short-stack).

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

[tests/galaxy.yml](tests/galaxy.yml)
[tests/stack.yml](tests/stack.yml)

Usage
-----

After installing [Short Stack](https://github.com/poetic/short-stack)
* At the bottom of ~/.galaxy.yml put:

```- src: https://github.com/poetic/short-stack-drupal
  name: drupal```
* At the bottom of the roles section in ~/.stack.yml file put:
`- drupal`

License
-------

[MIT](LICENSE)

Author Information
------------------

[Poetic Systems](http://poeticsystems.com)
