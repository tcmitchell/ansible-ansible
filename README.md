Ansible
=========

Install the latest version of ansible.

Requirements
------------

Any version of ansible.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - ansible-ansible

Example Usage
-------------

```shell
# Install ansible from apt
sudo apt-get install ansible

# clone this repository
git clone https://github.com/tcmitchell/ansible-ansible

# Install the latest ansible
ansible-playbook -b -i "localhost," -c local ansible-ansible/ansible-playbook.yml
```

License
-------

MIT

Author Information
------------------

https://github.com/tcmitchell
