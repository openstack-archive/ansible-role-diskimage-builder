==============================
ansible-role-diskimage-builder
==============================

Ansible role to manage Diskimage Builder!

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-diskimage-builder.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-diskimage-builder
* Bugs: https://bugs.launchpad.net/ansible-role-diskimage-builder

Description
-----------

Diskimage builder is a tool for building disk images, file system images and
ramdisk images.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install diskimage-builder
      hosts: nodepool
      roles:
        - ansible-role-diskimage-builder
