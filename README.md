ansible_role_nvidia
===================

A small ansible role to install nvidia management library from Nvidia's rpm repository.

Basically a stripped down version of https://github.com/NVIDIA/ansible-role-nvidia-driver/


Role Variables
--------------

nvidia_driver_branch: the driver branch. Check https://docs.nvidia.com/datacenter/tesla/index.html for the latest released one.


Example Playbook
----------------


    - hosts: servers
      roles:
         - { ansible_role_nvidia }

License
-------

BSD

Author Information
------------------

Simppa Äkäslompolo, Aalto Scientific Computing
