coffeesprout.proxmox-vm
=========

Create a proxmox VM


Role Variables
--------------

TODO: Please check the defaults / example in test

Dependencies
------------

No real dependency, but you might also like to create FreeBSD installable iso's using: coffeesprout.freebsd-iso
Or if you'd rather roll EL like systems: coffeesprout.ks-oem-drv

In both cases you will generate an iso for the install to take place.


Example Playbook
----------------

It makes more sense to look into the test folder. Because many vars are required some magic can be applied by using group\_vars and host\_vars for provisioning the VM's
I got some inspiration from here: https://github.com/UdelaRInterior/ansible-role-proxmox-create-kvm

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
