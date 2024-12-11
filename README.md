Role Name
=========

This role installs tigervnc on the workstation and creates a desktop file "UR VNC",
which establishes a vnc connection to the UR.

Requirements
------------

This role only works if the role install_vnc has been run previoulsy.

Role Variables
--------------



Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - install_vnc_viewer

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
