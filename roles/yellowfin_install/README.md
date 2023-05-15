Role Name
=========

Yellowfin 8.0 installation script. 

Requirements
------------

- Install prerequisite java, tomcat (This ansible script is not covering this, and assuming that they are already present on the VM)
- Download mysql connector jar and odbc jar and your yellowfin license file

Role Variables
--------------

Mainly the artifactory URL, from where to download the required jars, and yellowfin URl to download the yellowfin jar. 

Dependencies
------------

There can be dependencies, but I have not included them in this script. e.g. I had to use a vault to keep license file. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
