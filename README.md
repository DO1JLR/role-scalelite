[![MIT License](https://raw.githubusercontent.com/roles-ansible/role-scalelite/master/.github/license.svg?sanitize=true)](https://github.com/roles-ansible/role_scalelite/blob/master/LICENSE)
![Ansible Lint check](https://github.com/roles-ansible/role-scalelite/workflows/Ansible%20Lint%20check/badge.svg)
![Ansible check debian:buster](https://github.com/roles-ansible/role-scalelite/workflows/Ansible%20check%20debian:buster/badge.svg)

# role-scalelite
Ansible role to deploy scalelite without docker

**IN DEVELOPMENT - NOT FOR PRODUCTION USE!**

The scalelite repository can be found there:
https://github.com/blindsidenetworks/scalelite


 What is this role doing?
--------------------
 + First we do a simple version check, if this is enabled in the config. (disabled by default)
 + Next, we install the dependencies needed for scalelite.
 + We set up the scalelite user.
 + We set up some global ruby parameter like /etc/gemrc
 + rubyenv...
